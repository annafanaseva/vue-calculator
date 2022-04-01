

<template>
  <div id="app">
    <HelloWorld />
    <AppCalculator title="Calculator"/>  
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import AppCalculator from './components/AppCalculator.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    AppCalculator
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

  .HelloWorld{
    color: white;
  }
}
</style>
