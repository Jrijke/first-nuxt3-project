<template>
  <section>
    <h1>Welcome to the homepage</h1>
    <Counter />
  </section>
</template>

<script setup lang="ts">
  useHead({
    title: 'My App | Homepage',
    meta: [{ name: 'description', content: 'My amazing site.' }],
    bodyAttrs: {
      class: 'home-page',
    },
  });
</script>
