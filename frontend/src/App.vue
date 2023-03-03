<script setup lang="ts">
const request = async () => {
  const resp = await fetch('/api');
  console.log(await resp.json())
}
request();
</script>

<template>
  
</template>

<style scoped>

</style>
