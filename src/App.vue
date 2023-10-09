<script>
import Hero from './components/Hero.vue';

export default {
  name: "App",
  components: {
    Hero,
  },
  data() {
    return {
      text: "La mia prima app con Vite!"
    }
  },
}
</script>

<template>
  <Hero />
  <h1>{{text}}</h1>
</template>

<style>

</style>