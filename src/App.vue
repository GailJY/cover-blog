<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view />
    
  </div>
</template>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin:0;
  padding:0;
  border:0;
  font-size:100%;
  font:inherit;
  vertical-align:baseline;
}
body{
  width: 100%;
  *zoom: 1; 
  margin:0;
  font-size:14px;
}
body:before, body:after {
  content: "";
  display: table; 
}
hr{
  border:0;
}
a{
  text-decoration:none;
}
.router-link-active{
  color:#666666;
}
</style>
