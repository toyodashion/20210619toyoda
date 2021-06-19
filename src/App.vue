<template>
  <div id="app">
    <Header/>
    <router-view></router-view>
    <footer>
      <small>&copy;ShionToyoda.AllRights.Reserved</small>
    </footer>
  </div>
</template>

<script>

</script>

<style>
body{
  margin:0;
  padding:0;
  width:100%;
}

footer{
  display: flex;
  flex-direction:column;
  align-items: center;
  justify-content: flex-end;
  height: 50px;
  font-family: 'Viaoda Libre', cursive;
  background:white;
}

small{
  font-size: 10px;
  padding-bottom: 10px;
}
</style>

</style>

<script>
import Header from 'components/header.vue'
export default{
  components:{
    Header
  }
}
</script>