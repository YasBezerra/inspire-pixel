<script setup>
import fotografo from "../assets/fotografo.png"

</script>

<template>
    <section class="banner">
        <div>
            <h1>Onde a paisagem vira <span>inspiração</span>.</h1>
            <p>Explore paisagens, cores e luzes que inspiram novas histórias através da fotografia.</p>
        </div>

        <img :src="fotografo" alt="fotográfo">
    </section>

</template>

<style scoped lang="scss">

.banner {
    display: flex;
    justify-content: space-between;
    margin: 2rem;
    font-family: "Poppins", sans-serif;

    h1{
        font-size: 3.6rem;

        span{
            color: #E1306C;
            font-size: 4.5rem;
        }
    }
}

div{
    width: 50%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

img {
  width: 48% ;
  height: 38%;
   
}

</style>