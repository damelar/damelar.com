<script setup>
import { RouterLink, RouterView } from 'vue-router'
</script>

<template>
  <header>
    <div class="wrapper">
      <h1>Daniel Melo Aguilar</h1>
      
      <div class="social">
        <a href="https://github.com/damelar" target="_blank">GitHub</a>
        |
        <a href="https://www.linkedin.com/in/danielmeloaguilar/" target="_blank">Linkedin</a>
      </div>

        <nav>
          <RouterLink to="/about">Sobre</RouterLink>
          |
          <RouterLink to="/projects">Projetos</RouterLink>
          |
          <RouterLink to="/publications">Publicações</RouterLink>
        </nav>
      </div>
    </header>
    
  <RouterView />
</template>

<style scoped>

.social {
  text-align: center;
}
nav {
  margin-top: 10px;
  width: 100%;
  text-align: center;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}
</style>
