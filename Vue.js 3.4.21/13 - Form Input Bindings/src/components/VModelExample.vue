<script setup>
import { ref } from 'vue';

const text = ref('');
</script>

<template>
  <input type="text" v-model="text" />
  <p>Input value is: {{ text }}</p>
</template>

<style scoped></style>