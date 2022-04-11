<template>
  <div id="app">
    <TitoloNuovo></TitoloNuovo>
    <HeroTest></HeroTest>
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TitoloNuovo from './components/TitoloNuovo.vue'
import HeroTest from './components/HeroTest.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    TitoloNuovo,
    HeroTest
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
