<script setup lang="ts">
const { imgSrc } = defineProps<{ imgSrc: string }>();
</script>

<template>
  <img :src="'/assets/logos/' + imgSrc" class="h-12" />
</template>