<script setup lang="ts">
const runtimeConfig = useRuntimeConfig();
</script>

<template>
  <h1>Hello world!</h1>
  <code style="white-space: pre-wrap">
    {{ runtimeConfig.public }}
  </code>
</template>
