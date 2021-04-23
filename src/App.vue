<template>
  <div id="app">
    <img class="center" alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <TailwindCSSDemo/>
    <PlanetChart/>    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import PlanetChart from './components/PlanetChart.vue'
import TailwindCSSDemo from './components/TailwindCSSDemo.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    PlanetChart,
    TailwindCSSDemo
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
