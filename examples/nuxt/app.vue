<script setup lang="ts">
import { links } from 'unplugin-fonts/head'
import src from 'unfonts.css?raw'
</script>

<template>
  <h1>Hello Nuxt!</h1>
  <h2>I'm using a local font !</h2>
  <pre>links: {{ links }}</pre>
  <pre>src: {{ src }}</pre>
  <a href="https://vitejs.dev/guide/features.html" target="_blank">Documentation</a>
</template>

<style>
:root {
  font-family: "Crimson Pro", Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

a {
  font-family: "Open Sans", Avenir, Helvetica, Arial, sans-serif;
}

pre {
  text-align: left;
}

h2 {
  font-family: "Dancing Script", sans-serif;
  font-size: 3rem;
  font-weight: 600;
}
</style>