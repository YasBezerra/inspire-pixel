<script setup>
    defineProps(["imagem"]); 

</script>

<template>
    <div class="card">
    <img :src="imagem" alt="Imagens de paisagem">
    </div>
</template>

<style scoped lang="scss">

.card {

    img{
        width: 293px;
        height: 500px;
        border-radius: 10px;
        display: flex;
        object-fit: cover;
        gap: 10px;
    }
}
</style>