<script setup lang="ts">
defineProps<{ msg: string }>();
</script>

<template>
  <h1 class="font-bold underline">{{ msg }}</h1>
  <a href="https://tailwindcss.com/docs/installation/using-vite"
    >https://tailwindcss.com/docs/installation/using-vite</a
  >
</template>

<style scoped></style>
