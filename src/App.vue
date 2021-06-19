<template>
  <div id="app">
    <Header/>
    <router-view></router-view>
    <Footer/>
  </div>
</template>

<style>
body{
  margin:0;
  padding:0;
  width:100%;
}

</style>

<script>
import Header from './components/header.vue'
import Footer from './components/footer.vue'
export default{
  components:{
    Header,
    Footer
  }
}
</script>