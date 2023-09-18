<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import HeaderNavbar from "./components/HeaderNavbar.vue"
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />

  <h1 class="text-6x1 font-bold underline">Hola mundo</h1>

  <HeaderNavbar msg="prueba"></HeaderNavbar>
</template>

<style scoped>

</style>
