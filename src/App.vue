<template>
  <div id="wrapper">
    <Header />
    <Body />
    <Footer />
  </div>
</template>

<style lang="scss">
  @import 'App';
</style>

<script setup lang="ts">
  import Footer from './components/Footer.vue';
  import Body from './components/Body.vue';
  import Header from './components/Header.vue';
</script>
