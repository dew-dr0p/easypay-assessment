<template>
    <button class="rounded-3xl border p-2 px-14" :class="props.color ? 'border-primary border' : 'bg-primary text-white'">{{ props.text }}</button>
</template>

<script setup lang="ts">
const props = defineProps<{
    text: String,
    color?: Boolean
}>()
</script>