<script setup>
import Header from './components/Header.vue';
import Banner from './components/Banner.vue';
import inspire from './components/inspire.vue';
import Footer from './components/Footer.vue';

</script>

<template>
  <div class="global">
    <Header/>
    <Banner/>
    <inspire/>
    <Footer/>
  </div>
</template>

<style scoped lang="scss">
 .global {
  max-width: 1200px;
  width: 100%;
  margin: 0 auto;
}



</style>
