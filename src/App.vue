<template>
  <VueHeader />
  <nav>
    <router-link to="/">Home</router-link> |
    <router-link to="/about">Criador de Ameaças</router-link> |
    <router-link to="/vault">Cofre de Ameaças</router-link> |
  </nav>
  <router-view/>
</template>

<script>
import VueHeader from './components/VueHeader.vue';

export default {
  name: 'App',
  components: {
    VueHeader
  }
}
</script>

<style>
@font-face {
  font-family: 'tormenta';
  src: url('./fonts/Tormenta20.ttf') format('truetype');
  font-weight: normal;
  font-style: normal;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  height: 100vh;
  width: 100vw;
}

#app {
  color: #2c3e50;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

nav {
  align-items: center;
  border-bottom: 4px inset rgb(68, 2, 0);
  display: flex;
  height: 6vh;
}

nav a {
  align-items: center;
  color: rgb(168, 20, 0);
  display: flex;
  font-family: 'tormenta';
  font-size: 1.5em;
  height: 100%;
  justify-content: center;
  padding: 10px;
  text-decoration: none;
  width: 10%;
}

nav a:hover {
  background-color: rgba(248, 232, 202, 0.62);
  color: rgb(128, 20, 0);
}

nav a.router-link-exact-active {
  color: rgb(68, 2, 0);
}
</style>
