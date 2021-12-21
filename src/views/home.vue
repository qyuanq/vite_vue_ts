<script setup lang="ts">
import { ref } from 'vue'
import HelloWorld from '@/components/HelloWorld.vue'

defineProps<{ msg: string }>()

const count = ref(0)
</script>

<template>
  <HelloWorld></HelloWorld>
</template>

<style scoped>

</style>
