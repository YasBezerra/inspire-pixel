<script setup>
import iconsfooter from "../assets/iconsfooter.png"


</script>

<template>
<section class="footer">

<div>
<p>Contato</p>
<ul>
    <li><a href="">contato@inspiralens.com</a></li>
    <li><a href="">Central de ajuda</a></li>
    <li><a href="">Rio de Janeiro – Brasil</a></li>
</ul>
</div>

<div>
<p>Sobre</p>
<ul>
    <li><a href="">Politicas</a></li>
    <li><a href="">Politicas de privacidade</a></li>
    <li><a href="">Blog</a></li>
</ul>
</div>

<div>
<p>Assine nossa newsletter</p>
<input type="text" placeholder="Seu e-mail">

<button class="btnPink"> Inscrever-se </button>

</div>

<div class="redes"><img :src="iconsfooter" alt=""></div>

</section>

</template>

<style scoped lang="scss">

.footer {
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
}

div{
    flex: 1 1 30%;
    min-width: 200px;

    p {
        margin-left:10%;
        font-weight: 600;
        font-size: 1.5rem;
    }

    input{
        margin-left: 10%;
        background-color: #E6E6E63B;
        border-radius: 5px;
        width: 80%;
        height: 20%;
        border: none;
    }

    .btnPink {
        margin-left: 10%;
        margin-bottom: 10%;
        background-color: #E1306C;
        color: #FFF;
        height: 40px;
        width: 142px;
        border-radius: 5px;
        border: none;
        cursor: pointer;
    }
}

ul{
    li{
    list-style: none;
    text-decoration: none;
    display: flex;
    justify-content: space-between;

    a {
    text-decoration: none;
    color: #000;
    margin-bottom: 2% ;
    }
    }

}

.redes {
    padding: 3%;
    display: flex;
    justify-content: center;
    align-items: center;
}

</style>