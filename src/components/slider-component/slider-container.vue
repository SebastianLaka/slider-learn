<script setup>
import sliderItems from './slider-items.vue'
</script>
<template>
  <div class="slider-container">
    <sliderItems />
  </div>
</template>
<style lang="scss">
$main-bg-clr: rgb(7, 140, 248);
body {
    display: flex;
    justify-content: center;
    align-items: center;
    max-height: 100svh;
    background-color: $main-bg-clr;
  .slider-container {
    
  
    
    padding: 0.5em;
  }
}
</style>
