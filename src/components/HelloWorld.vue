<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
  </div>
  <h1 class="text-3xl font-bold underline">Hello world!</h1>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
