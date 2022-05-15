<script setup lang="ts">
import { RouterView } from "vue-router";
import Navbar from "@/components/Navbar.vue";
</script>

<template>
  <div class="bg-cyan-300">
    <Navbar />
    <RouterView />
  </div>
</template>

<style src="@/assets/css/styles.css">
</style>