<script setup>
defineProps({
  msg: {
    type: String,
    required: true,
  },
})
</script>

<template>
  <div class="greetings">
    <h1 class="green">{{ msg }}</h1>
    <h3>
      Hello This is my First Vue JS webpage
    </h3>
  </div>
</template>

<style scoped>

</style>
