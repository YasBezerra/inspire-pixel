<script setup>
import Card from './Card.vue';
import axios from 'axios';
import { ref } from "vue";

const imagens = ref ([]);

   async function carregarImagens () {
    const res = await axios.get("https://picsum.photos/v2/list?page=3&limit=30");
    console.log(res)

    imagens.value = res.data
    }

    carregarImagens();

</script>

<template>
    <h2>Inspire-se</h2>
    <section class="inspire">
        <Card v-for=" img in imagens "
        :imagem="img.download_url"/>
    </section>

</template>

<style scoped lang="scss">

h2 {
    margin-left: 5% ;
    font-family: "Poppins", sans-serif;
    font-weight: 400;
    font-size: 2.2rem;
}

.inspire {
    display: grid;                                
    grid-template-columns: repeat(4, minmax(0, 1fr));        
    gap: 70px;
    justify-items: center;   /* centraliza os cards */
    margin-left: 2rem;

@media (max-width: 600px) {
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 39px;
    justify-content: center;
    margin-left: 0;
}
}
</style>