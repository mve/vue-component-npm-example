<script setup lang="ts">
import { ref } from 'vue'

defineProps({
      msg: { type: String }
    }
)

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>

  <div class="card">
    <button type="button" @click="count++">count is {{ count }}</button>
  </div>
</template>

<style scoped>
h1 {
  color: #7e22ce;
}
</style>
