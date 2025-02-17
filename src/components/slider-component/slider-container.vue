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
body{
    .slider-container{
    background-color: $main-bg-clr;
    height: 100svh;
    padding: .5em;
    }
}
</style>
