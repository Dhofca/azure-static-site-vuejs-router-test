<template>
  <div class="about">
    <h1>Dynamic</h1>
    <div>{{ useRoute().params.uuid }}</div>
  </div>
</template>

<script setup>
import { useRoute } from "vue-router";

</script>