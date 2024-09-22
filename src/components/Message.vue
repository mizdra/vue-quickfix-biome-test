<template>
  <span>{{ msg.toUpperCase() }}</span>
  <span>{{  }}</span>
</template>

<script setup lang="ts">
defineProps<{msg: string}>()

</script>
