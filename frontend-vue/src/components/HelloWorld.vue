<script setup lang="ts">

defineProps<{ msg: string }>()

</script>

<template>
  <h1>{{ msg }}</h1>

</template>

<style scoped>
h1{
  text-align: center;
  width: 100vw;
}
</style>
