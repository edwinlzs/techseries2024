<script setup lang="ts">
const { label, imgSrc } = defineProps<{ label: string, imgSrc: string }>();
</script>

<template>
  <div class="flex flex-col items-center">
    <Logo :imgSrc="imgSrc" />
    <span class="mt-2">{{ label }}</span>
  </div>
</template>