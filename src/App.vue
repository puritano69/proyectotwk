<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <Home></Home>
    <contacto></contacto>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Contacto from './components/contacto.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    Contacto,
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
