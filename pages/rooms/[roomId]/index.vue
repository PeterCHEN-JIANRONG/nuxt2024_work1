<script setup>
const route = useRoute()
</script>
<template>
  <h1 class="h1">{{`客房詳細:${route.params.roomId}`}}</h1>
</template>
<style scoped></style>