<script setup>
import PostCard from "../components/PostCard.vue";
import usePost from "../composables/usePost.js";

const {posts: customNamePosts, fetchAll} = usePost();
fetchAll();

</script>

<template>
  <div class="flex flex-wrap flex-grow" >
    <PostCard v-for="post in customNamePosts" :post="post" ></PostCard>
  </div>
</template>

<style scoped>

</style>