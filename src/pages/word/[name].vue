<script setup lang="ts">
const props = defineProps<{ name: string }>()
</script>

<template lang="pug">
div this is a word {{ props.name }}
</template>
