<script setup>
import Post from './components/Post.vue';
const title = '匿名掲示板';
</script>

<template>
<header>
 <h1>{{ title }}</h1>
</header>
<ul>
  <Post/>
  <Post/>
  <Post/>
</ul>
</template>

<style scoped>
</style>
