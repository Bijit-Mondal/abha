<template>
  <ClientOnly>
    <Tetris
      class="h-[500px] w-full [mask-image:radial-gradient(450px_circle_at_center,#00C16A,transparent)]"
      :base="15"
      square-color="#fcd195"
    />
  </ClientOnly>
</template>

<script lang="ts" setup>
   import Tetris from '@/components/Tetris.vue'
</script>
