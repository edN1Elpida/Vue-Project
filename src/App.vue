<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <header>
    
    <nav>
      <RouterLink to="/">Profile</RouterLink>
      <RouterLink to="/skill">Skill</RouterLink>
    </nav>
    
    <div class="foto">
      <img alt="Vue logo" class="foto" src="@/assets/2v.jpeg" width="100" height="100" />
    </div>
      
    <div class="hero">
      <div class="wrapper">
        <HelloWorld msg="Rohmadani Dwi Oktaviansyah" msg1="WEB DEVELOPER"/>
      </div>
    </div>
  </header>

  <RouterView />
</template>

<style scoped>


.hero{
  background-color: #2c6cbc;
  border-radius: 10px;
  margin-top: 0.5rem;
}

header {
  line-height: 1.5;
  max-height: 100vh;
  flex-direction: column;
}

.foto {
  display: block;
  border-radius: 50%;
  height: 100px;
  width: 100px;
}

nav {
  width: 100%;
  font-size: 12px;
  text-align: center;
  margin-top: 2rem;
}

nav a.router-link-exact-active {
  color: var(--color-text);
}

nav a.router-link-exact-active:hover {
  background-color: transparent;
}

nav a {
  display: inline-block;
  padding: 0 1rem;
  border-left: 1px solid var(--color-border);
}

nav a:first-of-type {
  border: 0;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
    margin: 2rem;
    justify-content: center;
  }

  nav {
    text-align: left;
    margin-left: -1rem;
    font-size: 1rem;
    padding: 1rem 0;
    margin-top: 1rem;
  }
}
</style>
