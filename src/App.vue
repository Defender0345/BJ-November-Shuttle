<script setup>
import NavbarComp from '@/components/NavbarComp.vue'
import FooterComp from '@/components/FooterComp.vue'
</script>

<template>
  <div class="app">
    <NavbarComp />
    <router-view></router-view>
    <FooterComp />
  </div>
</template>

<style lang="scss">
@import '@/assets/_shared.scss';

* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

body {
  font-family: 'Open Sans', sans-serif;
  background: white;
  color: #333;
  line-height: 1.6;
}
</style>
