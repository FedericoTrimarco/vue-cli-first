<template>
  <section class="hero">
      <firstTitle />
  </section>
</template>

<script>
import firstTitle from './firstTitle.vue'
export default {
    name: 'Hero',
    components: {
        firstTitle
    }
}
</script>

<style scoped>
section{
    height: 100%;
    background-image: url('../assets/batman.jpg');
    background-size: cover;
    background-position: center;
}
</style>