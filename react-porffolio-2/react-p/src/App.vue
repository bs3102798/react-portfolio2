


<template>
  <div>
    <Navbar />
    <router-view />
  </div>
  <Footer />
</template>

<script setup>
import Navbar from './components/Navbar.vue';
import Footer from './components/Footer.vue';
</script>

<style scoped>
@import './styles.css';
</style>

