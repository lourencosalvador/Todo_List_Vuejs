<script setup lang="ts">
import { Avatar, AvatarFallback, AvatarImage } from '@/components/ui/avatar'
</script>

<template>
  <div class="h-14 w-full border-zinc-300 border-[1.3px] flex justify-between items-center px-6">
    <div class="flex space-x-2">
      <div class="w-[0.8rem] h-[0.8rem] rounded-full bg-red-500" />
      <div class="w-[0.8rem] h-[0.8rem] rounded-full bg-yellow-300" />
      <div class="w-[0.8rem] h-[0.8rem] rounded-full bg-green-500" />
    </div>

    <div
      class="relative w-[30rem] h-9 bg-zinc-200 rounded-[0.5rem] flex justify-center items-center"
    >
      <div class="flex">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-4 h-4 text-zinc-600"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M16.5 10.5V6.75a4.5 4.5 0 1 0-9 0v3.75m-.75 11.25h10.5a2.25 2.25 0 0 0 2.25-2.25v-6.75a2.25 2.25 0 0 0-2.25-2.25H6.75a2.25 2.25 0 0 0-2.25 2.25v6.75a2.25 2.25 0 0 0 2.25 2.25Z"
          />
        </svg>
        <p class="text-sm font-light text-zinc-600">Appname.com</p>
      </div>
      <div class="absolute left-[28rem]">
        <svg
          xmlns="http://www.w3.org/2000/svg"
          fill="none"
          viewBox="0 0 24 24"
          stroke-width="1.5"
          stroke="currentColor"
          class="w-4 h-4 text-zinc-600 font-semibold"
        >
          <path
            stroke-linecap="round"
            stroke-linejoin="round"
            d="M16.023 9.348h4.992v-.001M2.985 19.644v-4.992m0 0h4.992m-4.993 0 3.181 3.183a8.25 8.25 0 0 0 13.803-3.7M4.031 9.865a8.25 8.25 0 0 1 13.803-3.7l3.181 3.182m0-4.991v4.99"
          />
        </svg>
      </div>
    </div>

    <div class="w-36 h-[5rem]"></div>
  </div>
</template>
