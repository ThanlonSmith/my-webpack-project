<template>
  <div id="app">
    <img src="./assets/logo.png"><br>
    <router-link :to="{name:'Home'}">首页</router-link>
    <router-link :to="{name:'Course',query:{userid:1}}">免费课程</router-link>
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
