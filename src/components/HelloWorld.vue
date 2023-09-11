<script setup lang="ts">
defineProps<{ msg: string }>()
</script>

<template>
  <div class="flex justify-center items-center text-blue-500">
    <h1>{{ msg }}</h1>
  </div>
</template>

<style scoped></style>
