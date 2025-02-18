<template>
  <div class="slider-container">
    <img class="slider-container__image" src="../img/dodge-viper.jpg" alt="Dodge Viper SRT-10" />
  </div>
</template>
<style lang="scss">
$main-bg-clr: rgb(7, 140, 248);
body {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100svh;
  background-color: $main-bg-clr;
  padding: 1em;
  .slider-container {
    display: flex;
    max-height: 35em;
    &__image {
      object-fit: contain;
      max-height: 35em;
    }
  }
}
</style>
<script setup>
</script>