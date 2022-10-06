<template>
  <div>
    <h1>{{ home.title }}</h1>
  </div>
</template>

<script lang="ts" setup>
const home = reactive({
  title: 'hello',
})
</script>

<style scoped></style>
