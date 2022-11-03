<script setup lang="ts">
defineProps<{
  msg: string
}>()
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Drink a cold beer!
    </h3>
    <p>What is the best flavor for your new product?</p>
  </div>
</template>

<style scoped>
.green h1 {
  font-weight: 500;
  font-size: 4.6rem;
  top: -10px;
}

.green h3 {
  font-size: 1.2rem;
}

.greetings h1,
.greetings h3 {
  text-align: center;
}

@media (min-width: 1024px) {
  .greetings h1,
  .greetings h3 {
    text-align: left;
  }
}
</style>
