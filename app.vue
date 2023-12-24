<template>
  <div>
    <NuxtWelcome />
  </div>
</template>

<script setup lang="ts">
// $hello is not available when typescript is installed
const {$hello} = useNuxtApp()
console.log($hello())
</script>
