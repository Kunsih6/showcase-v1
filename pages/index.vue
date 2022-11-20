<template>
  <h1>Test</h1>
</template>

<script setup>
const story = await useAsyncStoryblok("home", { version: "draft" });
console.log(story);
</script>
