<script setup>
const projects = [
  {
    title: "GearTrail",
    tech: "HTML · CSS",
    image: "/images/geartrail.png",
    alt: "GearTrail landing page",
    description:
      "A premium landing page built for an outdoor exploration brand featuring a high-impact hero section, clean typography, and seamless layout design.",
    github: "",
    live: "",
  },
  {
    title: "The Flow Gallery",
    tech: "HTML · CSS · Grid",
    image: "/images/flow-gallery.png",
    alt: "The Flow Gallery website",
    description:
      "An elegant, interactive media portfolio gallery styled with structural CSS filters, responsive card modules, and smooth visual hover layers.",
    github: "",
    live: "",
  },
  {
    title: "Scented Co.",
    tech: "HTML · Bootstrap",
    image:
      "https://s3.amazonaws.com/shecodesio-production/uploads/files/000/180/563/original/Screenshot_2026-06-19_125922.png?1781866770",
    alt: "Scented Co. website",
    description:
      "A multi-page candle store built using Bootstrap. Features a product grid, image carousel, contact form and smooth scroll animations, styled entirely with Bootstrap, no external CSS.",
    github: "",
    live: "https://nonhlanhlakunene.github.io/lca-html-css-exercises/",
  },
];
</script>

<template>
  <section id="projects">
    <div class="container section-card">
      <h2>Projects</h2>
      <div class="accent-line"></div>
      <p>Here are some projects I've worked on during my training:</p>
      <div class="projects-grid">
        <div
          class="project-card"
          v-for="project in projects"
          :key="project.title"
        >
          <div class="project-screenshot">
            <img :src="project.image" :alt="project.alt" />
          </div>
          <div class="project-tech">{{ project.tech }}</div>
          <h3>{{ project.title }}</h3>
          <p>{{ project.description }}</p>
          <div class="project-links">
            <a
              v-if="project.live"
              :href="project.live"
              target="_blank"
              rel="noopener"
              class="btn-project"
              >View Project</a
            >
            <a
              v-if="project.github"
              :href="project.github"
              target="_blank"
              rel="noopener"
              class="btn-docs"
              >GitHub</a
            >
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
