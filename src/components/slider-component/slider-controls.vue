<template>
    <div class="buttons-area">
        <button class="buttons-area__left"><img src="../icons/arrow-left.svg" alt="slider arrow left"></button>
        <button class="buttons-area__right"><img src="../icons/arrow-right.svg" alt="slider arrow right"></button>
    </div>
</template>
<style scoped lang="scss">
.buttons-area{
    display: flex;
    position: absolute;
    justify-content: space-between;
    top: 50%;
    width: 100%;
    height: calc(100% + .3%);
    transform: translateY(-50%);
    &__left, &__right{
        padding: 1em 1.5em;
        border: none;
        background-color: rgba(0,0,0, .5);
        cursor: pointer;
    }
}
</style>