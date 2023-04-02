<script setup lang="ts">
import { RouterView } from 'vue-router'
import PageHeader from '@/components/PageHeader.vue'
import PageFooter from '@/components/PageFooter.vue'
</script>

<template>
  <main class="container">
    <PageHeader />
    <RouterView />
    <PageFooter />
  </main>
</template>

<style scoped></style>
