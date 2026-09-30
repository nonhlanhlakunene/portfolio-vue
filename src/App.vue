<script setup>
import { RouterView } from "vue-router";
import ThemeToggle from "./components/ThemeToggle.vue";
import LoaderScreen from "./components/LoaderScreen.vue";
</script>

<template>
  <ThemeToggle />
  <div class="blob-3"></div>
  <LoaderScreen />
  <RouterView />
</template>
