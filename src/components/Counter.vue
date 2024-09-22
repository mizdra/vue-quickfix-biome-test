<script setup lang="ts">
import { ref } from 'vue'

defineProps<{
  initialCount?: number
}>()
const count = ref()

</script>

<template>
  <div>
    <button @click="count++">count is: {{ count }}</button>
  </div>
</template>
