<script setup lang="ts">
import BaseLink from '@/components/BaseLink.vue';
</script>

<template>
  <div class="about">
    <div class="about-content">
        <h1 style="margin-top: 0">Stable UI</h1>
        <h2>About</h2>
        <p>
        This UI is integrated into <strong>stable-diffusion.cpp</strong> and adapted specifically for this project.
        </p>
        <p>
        It is based on <strong>stable-ui</strong>, originally developed as a frontend for <strong>AI Horde</strong> and later adapted for local generation APIs.
        </p>
        <p>
        Upstream projects:
        <a href="https://github.com/LostRuins/stable-ui" target="_blank" rel="noopener noreferrer">LostRuins/stable-ui</a>,
        <a href="https://github.com/henk717/stable-ui" target="_blank" rel="noopener noreferrer">henk717/stable-ui</a>,
        <a href="https://github.com/ayunami2000/stable-ui" target="_blank" rel="noopener noreferrer">ayunami2000/stable-ui</a>,
        based on the original
        <a href="https://github.com/aqualxx/stable-ui" target="_blank" rel="noopener noreferrer">aqualxx/stable-ui</a>
        by <strong>aqualxx</strong>.
        </p>
        <p>
        Special thanks to all maintainers and contributors.
        </p>
    </div>
  </div>
</template>

<style scoped>
h3, h1 {
    margin-bottom: 0;
}

.about {
    width: 100%;
    font-size: 1.1rem;
    display: flex;
    justify-content: center;
}

.about-content {
    width: 60%
}

.faq {
    font-size: 1.05rem
}

@media only screen and (max-width: 1000px) {
    .about-content {
        width: 80%;
    }
}

@media only screen and (max-width: 700px) {
    .about-content {
        width: 100%;
    }
}
</style>
