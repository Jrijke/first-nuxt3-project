<template>
  <main>
    <AppHeader />
    <slot />
    <AppFooter />
  </main>
</template>

<style>
  main,
  main > section {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
  }
</style>
