<script setup>
import { ref } from "vue";
const isLight = ref(false);
function toggleTheme() {
  isLight.value = !isLight.value;
  document.body.classList.toggle("light", isLight.value);
}
</script>

<template>
  <button
    class="theme-toggle-btn"
    type="button"
    aria-label="Switch between light and dark mode"
    @click="toggleTheme"
  >
    <i class="fa-solid fa-moon moon-icon"></i>
    <i class="fa-solid fa-sun sun-icon"></i>
  </button>
</template>
