<script setup>
defineProps({
  post: Object
})

</script>

<template>
  <div>
    <h2>{{ post.userId }}</h2>
    <p>{{ post.body }}</p>
  </div>
</template>

<style scoped>

</style>