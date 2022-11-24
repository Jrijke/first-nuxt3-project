<template>
  <button @click="increment()">Incerement</button>
  <p>{{ count }}</p>
  <button @click="decrement()">Decrement</button>
</template>

<script setup>
  const count = useState('count', () => Math.round(Math.random() * 1000));

  function increment() {
    count.value++;
  }

  function decrement() {
    count.value--;
  }
</script>
