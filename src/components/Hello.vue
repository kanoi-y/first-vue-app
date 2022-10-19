<script setup>
const props = defineProps({
    message:String
})
</script>

<template>
  <h2>初めてのコンポーネント</h2>
  <p>{{ props.message }}</p>
</template>
