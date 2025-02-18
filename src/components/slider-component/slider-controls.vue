<template>
    <div class="buttons-area">
        <button class="buttons-area__left"><</button>
        <button class="buttons-area__right">></button>
    </div>
</template>
<style scoped lang="scss">
.buttons-area{
    position: absolute;
    width: 100%;
    display: flex;
    justify-content: space-between;
    top: 50%;
    transform: translateY(-50%);
    &__left, &__right{
        padding: 1em 1.5em;
        border: none;
        // background-color: transparent;
        cursor: pointer;
    }
}
</style>