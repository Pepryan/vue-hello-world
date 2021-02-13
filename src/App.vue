<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/FR_Graphic_Design.png">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Design/>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import Design from './components/Design.vue'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    Design
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
