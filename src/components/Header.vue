<script setup>
import { Icon } from "@iconify/vue";
import logo from "../assets/logo.png"

</script>

<template>
<header>
    <img :src="logo" alt="Imagem da logo marca">
   <nav>
    <ul>
    <li>
        <a href="">
            <Icon class="search-icon" icon="material-symbols:search" color="#E1306C" />
        </a>
    </li>
    <li>
        <a href="">Início</a>
    </li>
    <li>
        <a href="">Galeria</a>
    </li>
    <li>
        <a href="">Favoritos</a>
    </li>
    <li>
        <a href="">
            <Icon class="charm:person" icon="octicon:person-16" color="#E1306C"/>
        </a>
        <img src="" alt="">
    </li>
    </ul>
   </nav>


</header>
</template>

<style scoped lang="scss">

header{
    justify-content: space-between;
    display: flex;
    align-items: center;

    img{
        width: 5%;
        height: 5%;
    }

    ul {
        display: flex;
        list-style: none;
        gap: 1.5rem;
        flex-wrap: wrap;
        align-items: center;


    }

    a {
        text-decoration: none;
        color: black;
    }
    
}

</style>