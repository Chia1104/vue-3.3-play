<script lang="ts" setup>
import { defineModel } from "vue";
const modelValue = defineModel()
</script>

<template>
  <input v-model="modelValue" type="text" />
</template>

<style scoped>
input {
  border: 1px solid #ccc;
  border-radius: 4px;
  padding: 0.5em;
  font-size: 1em;
  width: 100%;
}
</style>
