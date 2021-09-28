<template>
  <div id="app">
    <titolo/>
    <hero/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import titolo from '@/components/titolo.vue'
import hero from './components/hero.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    titolo,
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
