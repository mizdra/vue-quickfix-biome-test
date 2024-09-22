<template>
  <counter  />
</template>

<script setup lang="ts">
import Counter from './components/Counter.vue';
export default { components: { Counter } };
</script>
<style scoped>
.counter { color: red; }
</style>