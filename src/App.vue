<template>
  <div id="app">
    <header>
      <router-link to="/"><h1>ShionToyoda</h1></router-link>
      <nav class="nav__pc">
        <ul>
          <router-link to="/about">ABOUT</router-link>
          <router-link to="/service">SERVICE</router-link>
          <router-link to="/news">NEWS</router-link>
        </ul>
      </nav>
    </header>
    <router-view></router-view>
    <footer>
      <small>&copy;ShionToyoda.AllRights.Reserved</small>
    </footer>
  </div>
</template>

<style>
body{
  margin:0;
  padding:0;
  width:100%;
}

header{
  height: 130px;
  width: 100%;
  position: fixed;
  background-color:white;
}

h1{
  font-size: 60px;
  font-family: 'Viaoda Libre', cursive;
  display: flex;
  justify-content: center;
  padding: 10px 0;
  margin:0;
}

a{
  text-decoration: none;
  color: black;
}

.nav__pc{
  display: flex;
  justify-content: center;
}

.nav__pc ul{
  display: flex;
  justify-content: space-around;
  width: 50%;
  margin:0;
  font-family: 'Viaoda Libre', cursive;
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

