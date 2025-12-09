<script setup>
    defineProps(["imagem"]); 
    import { ref } from 'vue';
    
    const likes = ref(0);

</script>

<template>
    
    <div class="card">
    <img :src="imagem" alt="Imagens de paisagem">
    <button @click="likes++"> {{ likes }} ❤</button>
    </div>
</template>

<style scoped lang="scss">

.card {
    position: relative;
    transition: 0.5s ease;
    overflow: hidden;

    .card:hover {
        transform: translateY(-4px);
        box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
    }

    img{

        width: 293px;
        height: 500px;
        border-radius: 10px;
        display: block;
        object-fit: cover;
        gap: 5px;
        object-fit: cover;
        flex-wrap: wrap;
    }

    button {
    position: absolute;
    top: 10px;
    right: 10px;
    background: transparent;
    border: none;
    cursor: pointer;
    font-size: 24px;       
    color: white;        
    padding: 0;
    transition: 0.2s ease;
    }

    button:hover {
    transform: scale(1.2); 
    opacity: 0.9;
    }

@media (max-width: 600px) {

  .card {
    width: 48%;
    display: flex;
    flex-direction: column; /* IMPORTANTE */
    justify-content: space-between;
    flex-wrap: nowrap; /* evita quebra estranha */
  }

  img {
    width: 100%; /* aqui resolve */
    height: 250px;
  }

  button {
    font-size: 18px;
    top: 6px;
    right: 6px;
  }
}
}
</style>