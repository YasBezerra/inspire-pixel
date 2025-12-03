<script setup>
import Card from './Card.vue';
</script>

<template>
    <h2>Inspire-se</h2>
    <section class="inspire">
        <Card imagem="https://i.pinimg.com/736x/e8/26/dc/e826dcad1e8f95c65218e8f9c4ab4902.jpg"/>
        <Card imagem="https://i.pinimg.com/736x/d0/d3/81/d0d381a9e6a6b1b3b31a7f2f4bdd3f24.jpg"/>
        <Card imagem="https://i.pinimg.com/736x/f5/52/36/f552363a9488166b6f811642aff10b78.jpg"/>
    </section>

</template>

<style scoped lang="scss">
.inspire, h2 {
    display: flex;
    gap: 15px;
    justify-content: space-between;
    margin: 2rem;
}
</style>