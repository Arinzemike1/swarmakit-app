<script setup lang="ts">
import { defineProps } from "vue";

defineProps<{ msg: string }>();
</script>

<template>
  <h1>{{ msg }}</h1>
  <button>Learn more</button>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
