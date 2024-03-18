<script setup>
import NavBar from '@/components/NavBar.vue'
import Main from '@/components/Main.vue'
import BodyTask from '@/components/BodyTask.vue'
import Aside from '@/components/Aside.vue'
</script>

<template class="w-screen h-screen bg-slate-200 overflow-hidden">
  <NavBar />
  <div class="flex">
    <Main />
    <div class="w-96 h-screen">
      <BodyTask />
    </div>
    <aside class="flex-1 border-zinc-200 border-l-[1.5px]">
      <Aside />
    </aside>
  </div>
</template>

<style scoped></style>
