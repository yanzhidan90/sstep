<template>
  <div id="app">
    <start />
    <!--<img src="./assets/logo.png">
    <hello-world msg="Welcome to Your Vue.js App" />-->
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import start from './components/Start'

export default {
  name: 'App',
  components: {
    // HelloWorld,
    start
  }
}
</script>

<style>
/*#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}*/
</style>
