<script setup lang="ts">
</script>

<template>
  <div class="hero">
    <h1 class="hero__title">Ethan Hogge</h1>
    <p class="hero__subtitle">Software Developer. Full stack dev, defense systems to Vue 3 modernization</p>
    <img src="/src/assets/ethan-photo.jpg" alt="Ethan image" />
    <button class="hero__button" @click="window.location.href='mailto:ethan@example.com'">Email Me</button>
    <button class="hero__button" @click="window.location.href='https://www.linkedin.com/in/ethan-hogge/'">LinkedIn</button>
    <button class="hero__button" @click="window.location.href='https://github.com/ethanhogge'">GitHub</button>
    <button class="hero__button" @click="window.location.href='https://ethanhogge.com/resume.pdf'">Resume</button>
    <button class="hero__button" @click="window.location.href=''">View my work</button>
  </div>
</template>
