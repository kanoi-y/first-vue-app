<script setup>
import { ref } from "vue";
import Input from "./components/Input.vue";
import Hello from "./components/Hello.vue";

const name = ref("John Doe");
const address = ref("");
</script>

<template>
  <h1>Vue 3 入門</h1>
  <p>name:{{ name }}</p>
  <p>address:{{ address }}</p>
  <Input v-model="name" />
  <Input v-model="address" />
  <Hello :name="name" />
</template>
