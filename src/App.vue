<script setup>
import {ref} from 'vue'
import Header from './components/Header.vue';
import Main  from './components/Main.vue';
import Footer from './components/Footer.vue';
</script>

<template>
    <div class="page">
        <Header />
        <Main />
        <Footer />

    </div>

</template>

<style scoped>
html,
body,
#app {
  min-height: 100%;
  margin: 0;
}

.page {
  min-height: 100vh;
  color: white;
  background:
    radial-gradient(circle at 20% 25%, rgba(252, 247, 247, 0.18), transparent 12rem),
    radial-gradient(circle at 80% 35%, rgba(221, 203, 253, 0.16), transparent 16rem),
    #000235;
}

</style>