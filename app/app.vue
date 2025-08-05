<script setup lang="ts">
const runtimeConfig = useRuntimeConfig();
</script>

<template>
  <code style="white-space: pre-wrap">
    {{ runtimeConfig.public }}
  </code>
</template>
