<script setup lang="ts">

const props = defineProps<{label: string}>()

</script>

<template>
  <div>render: {{ props.label }}</div>
</template>
