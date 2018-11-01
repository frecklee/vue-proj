<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> |
      <router-link to="/ex">Ex</router-link>
      <!-- <p style="font-family: 'Noto Sans KR', sans-serif;">안녕하셍</p> -->
    </div>
    <router-view/>
  </div>
</template>

<style>
  @import url('https://fonts.googleapis.com/css?family=Arimo|Noto+Sans+KR|Bangers');
  #app {
    /* font-family: 'Avenir', Helvetica, Arial, sans-serif; */
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
  }
  
  #nav {
    padding: 10px;
        font-family: 'Bangers', cursive;
font-size: 25px;

  }
  
  #nav a {
    /* font-family: 'Noto Sans KR', sans-serif; */
    font-weight: bold;
    color: #2c3e50;
  }
  
  #nav a.router-link-exact-active {
    /* font-family: 'Noto Sans KR', sans-serif; */
    color: #42b983;
  }
</style>
