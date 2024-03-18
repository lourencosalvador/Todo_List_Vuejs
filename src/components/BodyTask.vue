<script setup>
import { ref, reactive } from 'vue'
import CardTasks from '@/components/CardTasks.vue'
</script>
<template>
  <div class="h-14 w-full border-zinc-200 border-b-[1.5px] mb-8"></div>
  <div class="px-4 mb-8">
    <div
      class="w-full h-10 border-zinc-300 flex space-x-2 border-[1.5px] rounded-[0.5rem] p-4 items-center"
    >
      <svg
        xmlns="http://www.w3.org/2000/svg"
        fill="none"
        viewBox="0 0 24 24"
        stroke-width="1.5"
        stroke="currentColor"
        class="w-4 h-4 font-semibold text-zinc-600"
      >
        <path
          stroke-linecap="round"
          stroke-linejoin="round"
          d="m21 21-5.197-5.197m0 0A7.5 7.5 0 1 0 5.196 5.196a7.5 7.5 0 0 0 10.607 10.607Z"
        />
      </svg>

      <input
        type="text"
        class="w-56 placeholder:text-[13.5px] bg-transparent outline-none text-zinc-600"
        placeholder="Search"
      />
    </div>
  </div>
  <div class="px-4 flex flex-col space-y-3">
    <CardTasks
      title="
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, earum voluptate. Est neque in voluptatem?"
    ></CardTasks>
    <CardTasks
      title="
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, earum voluptate. Est neque in voluptatem?"
    ></CardTasks>
    <CardTasks
      title="
 Lorem ipsum dolor sit amet consectetur adipisicing elit. Veritatis, earum voluptate. Est neque in voluptatem?"
    ></CardTasks>
  </div>
</template>
