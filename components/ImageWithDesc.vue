<script setup lang="ts">
const { imgSrc } = defineProps<{ imgSrc: string }>();
</script>

<template>
    <div class="flex gap-8 h-5/6">
        <img :src="'/assets/images/' + imgSrc" class="h-full" />
        <div>
            <slot />
        </div>
    </div>
</template>