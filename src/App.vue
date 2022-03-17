<template>
<div class="filler"></div>
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

.filler {
  background-image: url("../src/assets/back.jpg");
  background-size: cover;
  height: 77vh;
  width: 100vw;
}
</style>
