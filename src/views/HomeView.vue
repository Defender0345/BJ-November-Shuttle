<script setup>
import ServicesComp from '@/components/ServicesComp.vue'
import AboutComp from '@/components/AboutComp.vue'
import LightboxComp from '@/components/LightboxComp.vue'
import FormComp from '@/components/FormComp.vue'
</script>

<template>
  <main>
    <ServicesComp />
    <AboutComp />
    <LightboxComp />
    <FormComp />
  </main>
</template>

<style lang="scss">
@import '@/assets/_shared.scss';

h1 {
  font-size: 5rem;
}
</style>
