<template>
  <h1 class="text-3xl font-bold underline text-red-500">
    {{ aaa }}{{ test }}
  </h1>
</template>

<script setup lang="ts">
const aaa = "測試用"
</script>

<script lang="ts">
export default {
  data() { 
    return {
      test:'aaa',
    }
  },
}
</script>