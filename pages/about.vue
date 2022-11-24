<template>
  <section>
    <p>This page will be displayed at the /about route.</p>
    <Counter />
  </section>
</template>

<script setup lang="ts">
  useHead({
    title: 'My App | About page',
    meta: [{ name: 'description', content: 'My amazing site.' }],
    bodyAttrs: {
      class: 'about-page',
    },
  });
</script>
