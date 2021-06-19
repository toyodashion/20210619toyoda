<template>
  <header>
    <router-link to="/"><h1>ShionToyoda</h1></router-link>
    <nav class="nav__pc">
      <ul>
        <router-link to="/about" class="li">ABOUT</router-link>
        <router-link to="/service" class="li">SERVICE</router-link>
        <router-link to="/news" class="li">NEWS</router-link>
      </ul>
    </nav>
  </header>
</template>

<style>
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
  padding:0;
}

.li{
  padding:0 15px;
}

</style>