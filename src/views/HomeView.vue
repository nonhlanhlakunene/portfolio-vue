<script setup>
import NavBar from '../components/NavBar.vue'
import HeroSection from '../components/HeroSection.vue'
import AboutSection from '../components/AboutSection.vue'
import SkillsSection from '../components/SkillsSection.vue'
import ProjectsSection from '@/components/ProjectsSection.vue';
</script>

<template>
  <NavBar/>
  <main><HeroSection /><AboutSection/><SkillsSection/><ProjectsSection/>
  </main>
</template>
