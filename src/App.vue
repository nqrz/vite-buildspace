<script setup lang="ts">
function wave() {
  console.log('Hey!👋');
}
</script>

<template>
  <div class="bg-indigo-200 text-gray-800 h-screen flex flex-col justify-center items-center gap-4 px-4">
    <div class="bg-gradient-to-tr from-light-600 to-light-50 p-4">
      <h1 class="text-4xl">Hellooooo Web3!! 🌏</h1>
    </div>
    <div>
      <h2 class="text-2xl text-center">
        I am <strong><a target="_blank" class="link hover:text-3xl" href="https://nizarbaihaqi.com">Nizar Baihaqi</a></strong> from Indonesia 🆔. Still learning front end and that not stopped me from learning Web3 🔥.
      </h2>
    </div>
    <button class="btn p-4 text-xl" @click="wave">
      Wave at me 👋
    </button>
    <code>Created with <a target="_blank" class="link hover:text-lg" href="https://vitejs.dev">Vitejs</a> and <a target="_blank" class="link hover:text-lg" href="https://v3.vuejs.org/">Vue 3</a></code>
    <a target="_blank" class="w-6 transform hover:scale-110" href="https://nizarbaihaqi.com">
      <img src="./assets/logo.svg" alt="Logo Nizar Baihaqi">
    </a>
  </div>
</template>

<style>
#app {
  font-family: 'Noto Sans', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
