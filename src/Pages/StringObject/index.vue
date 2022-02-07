<template>
  <CodeComponent />
</template>

<script setup>
import { reactive } from "vue";
import CodeComponent from "../../components/CodeComponent.vue";
const msg = reactive({
  age: 185
});
</script>

<style>
</style>