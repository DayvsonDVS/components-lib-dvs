<template>
  <button :style="{ background: color }">
    <slot />
  </button>
</template>

<script setup lang="ts">
defineProps({
  color: {
    type: String,
    required: false,
    default: '#2fa'
  }
})
</script>

<style scoped lang="scss"></style>
