<template>
  <div class="slider-container">
    <div class="img-area">
      <sliderButtons />
    </div>
  </div>
</template>
<style lang="scss">
$main-bg-clr: rgb(7, 140, 248);

body {
  background-color: $main-bg-clr;
  padding: 1em;
  .slider-container {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 95svh;
    max-width: 1000px;
    margin: 0 auto;
    position: relative;
    z-index: 0;
    .img-area {
      position: absolute;
      background-image: url(@/assets/img/porsche-911-dakkar.jpg);
      background-size: cover;
      background-position: center center;
      background-repeat: no-repeat;
      margin: 0 auto;
      width: 100%;
      min-height: 75%;
      z-index: 1;
    }
  }
}
</style>
<script setup>
import sliderButtons from './slider-controls.vue'
</script>
