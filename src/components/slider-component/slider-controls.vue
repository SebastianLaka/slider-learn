<template>
  <div class="buttons-area">
    <button @click="clickButton('clickLeft')" class="buttons-area__left">
      <img src="@/assets/icons/arrow-left.svg" alt="slider arrow left" />
    </button>
    <button @click="clickButton('clickRight')" class="buttons-area__right">
      <img src="@/assets/icons/arrow-right.svg" alt="slider arrow right" />
    </button>
  </div>
</template>
<style scoped lang="scss">
.buttons-area {
  display: flex;
  position: absolute;
  justify-content: space-between;
  top: 50%;
  width: 100%;
  height: calc(100% + 0.3%);
  transform: translateY(-50%);
  &__left,
  &__right {
    padding: 1em 1.5em;
    border: none;
    background-color: rgba(0, 0, 0, 0.5);
    cursor: pointer;
    transition: background-color 0.3s ease-in-out;
  }
  &__left:hover,
  &__right:hover {
    background-color: transparent;
  }
}
</style>
<script>

export default{
emits:['clickRight', 'clickLeft'],
methods: {
    clickButton (event) {
        this.$emit(event)
        console.log(`ok ${event}`);
    },
}
}
</script>
