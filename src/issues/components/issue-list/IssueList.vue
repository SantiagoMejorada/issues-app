<script setup lang="ts">
import IssueCard from './IssueCard.vue';
</script>
<template>
  <IssueCard v-for="card of 20" :key="card" />
</template>

<style scoped></style>
