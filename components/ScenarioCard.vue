<template>
  <div class="card">
    <span :class="tagClass">{{ tag }}</span>
    <h3 class="mt-2">{{ title }}</h3>
    <p>{{ description }}</p>
    <div v-if="metric" class="metric-small mt-2">{{ metric }}</div>
  </div>
</template>

<script setup>
import { computed } from 'vue'

const props = defineProps({
  tag: { type: String, default: '' },
  title: { type: String, required: true },
  description: { type: String, required: true },
  metric: { type: String, default: '' },
  color: { type: String, default: 'blue' },
})

const tagClass = computed(() => ({
  tag: props.color === 'blue',
  'tag-green': props.color === 'green',
  'tag-orange': props.color === 'orange',
  'tag-red': props.color === 'red',
}))
</script>
