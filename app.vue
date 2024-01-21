<template>
  <NuxtClientFallback fallback-tag="span" fallback="500">
  </NuxtClientFallback>
  <NuxtLayout>
    <NuxtLoadingIndicator />

    <NuxtPage />
  </NuxtLayout>
</template>
<script setup lang="ts">
</script>