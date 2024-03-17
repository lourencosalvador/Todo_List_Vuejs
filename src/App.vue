<script setup>
import NavBar from '@/components/NavBar.vue'
import Main from '@/components/Main.vue'
</script>

<template class="w-screen h-screen bg-slate-200 overflow-hidden">
  <NavBar />
  <div class="flex space-x-5">
    <Main />
    <div class="w-80 h-screen bg-zinc-800"></div>
    <aside class="flex-1 bg-red-300"></aside>
  </div>
</template>

<style scoped></style>
