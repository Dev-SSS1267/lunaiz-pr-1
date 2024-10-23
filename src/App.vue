<script setup>
import Navbar from './components/navbar.vue'
import Hero from './components/hero.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>

  <Navbar/>

  <Hero>
    <template #head-txt>our ligiht illuminates your night</template>

  </Hero>

  <main class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
    <TheWelcome />
  </main>
</template>
