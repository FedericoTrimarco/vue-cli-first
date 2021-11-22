<template>
  <div id="app">
    <Hero />
  </div>
</template>

<script>
import Hero from './components/Hero.vue'

export default {
  name: 'App',
  components: {
    Hero,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  height: 100vh;
}
</style>
