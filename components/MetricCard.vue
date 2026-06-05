<template>
  <div class="card" style="text-align: center;">
    <div class="metric">{{ value }}</div>
    <div class="caption mt-2">{{ label }}</div>
  </div>
</template>

<script setup>
defineProps({
  value: { type: String, required: true },
  label: { type: String, required: true },
})
</script>
