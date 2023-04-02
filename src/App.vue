<script setup lang="ts">
import { RouterView } from 'vue-router'
import PageHeader from '@/components/PageHeader.vue'
</script>

<template>
  <main class="container">
    <PageHeader />
    <RouterView />
  </main>
</template>

<style scoped></style>
