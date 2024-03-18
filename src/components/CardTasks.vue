<template>
  <div class="w-full h-36 rounded-[0.8rem] border-zinc-200 border-[1.5px] p-3 flex flex-col gap-2">
    <div class="flex w-full justify-between items-center mb-2">
      <h1 class="text-[13px] text-zinc-800">Lourenço Cardoso</h1>
      <p class="text-[11px] font-medium text-zinc-500">5 months ago</p>
    </div>
    <h2 class="text-[12.5px] text-zinc-600 mb-1">{{ title }}</h2>

    <div class="flex space-x-3">
      <Button class="bg-zinc-300 text-zinc-800 h-8 w-16 rounded-[0.2rem] text-[12px]"
        >Button</Button
      >
      <Button class="bg-zinc-800 text-slate-200 h-8 w-16 rounded-[0.2rem] text-[12px]">work</Button>
      <Button class="bg-zinc-300 text-xinc-800 h-8 w-16 rounded-[0.2rem] text-[12px]"
        >Button</Button
      >
    </div>
  </div>
</template>

<script>
import { Button } from '@/components/ui/button'
export default {
  props: {
    title: {
      type: String,
      required: true
    }
  }
}
</script>
