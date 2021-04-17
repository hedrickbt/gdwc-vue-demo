<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <GdwcVueDemo msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import GdwcVueDemo from './components/GdwcVueDemo.vue'
// import '@gdwc/components/menu'


export default {
  name: 'App',
  components: {
    GdwcVueDemo
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
