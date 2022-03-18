<template>
<div class="filler">
<img  id="board" src="../src/assets/board.png"  />
</div>
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

#board {
  display: block;
  margin: 0 auto;
}
</style>
