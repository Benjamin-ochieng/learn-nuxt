<template>
  <div>
    <h1>Event number {{ pageId }}</h1>
  </div>
</template>

<script setup lang="ts">
// import { useRoute } from "vue-router";

const route = useRoute();
const pageId = route.params.id;

</script>

<style scoped></style>
