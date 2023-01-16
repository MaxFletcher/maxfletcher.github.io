<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <ul>
    <li><router-link to="/about-me">About me</router-link></li>
    <li><router-link to="/curriculum-vitae">Curriculum Vitae</router-link></li>
    <li><router-link to="/projects">Projects</router-link></li>
    <li><router-link to="/showcase">Showcase</router-link></li>
  </ul>

  <router-view></router-view>
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
