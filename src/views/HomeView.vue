<script setup>
import ServicesComp from '@/components/ServicesComp.vue'
import AboutComp from '@/components/AboutComp.vue'
import LightboxComp from '@/components/LightboxComp.vue'
</script>

<template>
  <main>
    <ServicesComp />
    <AboutComp />
    <LightboxComp />
  </main>
</template>

<style lang="scss">
@import '@/assets/_shared.scss';

h1 {
  font-size: 5rem;
}
</style>
