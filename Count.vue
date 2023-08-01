<script setup>
import { ref } from 'vue';
const count=ref(0)

function add(){
  count.value++
}
</script>

<template>
<div>
  <div>{{ count }}</div>
  <button @click="add">Click</button>
</div>
</template>

<style scoped>

</style>
