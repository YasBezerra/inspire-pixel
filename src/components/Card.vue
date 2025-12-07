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
        gap: 10px;
        object-fit: cover;
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
}
</style>