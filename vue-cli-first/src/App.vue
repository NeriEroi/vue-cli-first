<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld />
    <vueCLIfirst />
    <hero />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import vueCLIfirst from './components/vueCLIfirst.vue'
import hero from './components/hero.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    vueCLIfirst,
    hero
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
