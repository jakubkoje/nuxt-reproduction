<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script setup lang="ts">
// $hello is not available when @vueuse/motion/nuxt is enabled
const {$hello} = useNuxtApp()
// console.log($hello())
</script>
