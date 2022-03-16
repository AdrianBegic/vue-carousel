<template>
  <carouselComponent/>
  
</template>

<script>
import carouselComponent from '../src/components/carousel.vue'

export default {
  name: 'App',
  components: {
    carouselComponent,
  }
}
</script>

<style>
#app {
  margin: 0;
  padding: 0;
}
body {
  margin:0;
}
</style>
