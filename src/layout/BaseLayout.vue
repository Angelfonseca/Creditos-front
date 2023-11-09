<script setup>
import NavBar from '../components/NavBar.vue'
import Footer from '../components/Footer.vue'

</script>
<template>
  <header>
    <NavBar></NavBar>
  </header>
  <main>
    <Footer></Footer>
  </main>
  <slot/>
</template>
<style>

@import url('../assets/estilo.css');
</style>
