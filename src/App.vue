<template>
  <div id="app">
    <firstTitle />
  </div>
</template>

<script>
import firstTitle from './components/firstTitle.vue'

export default {
  name: 'App',
  components: {
    firstTitle,
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
