<template>
  <header class="vue-header">
    <h1 class="title">Fábrica das Ameaças de Arton</h1>
  </header>
</template>

<script>
export default {
  name: 'VueHeader'
}
</script>

<style>
 .vue-header {
   align-items: center;
   background-color: rgb(61, 1, 0);
   background-image: url('../assets/HeaderBg.svg');
   background-size: contain;
   display: flex;
   height: 8vh;
   justify-content: center;
   width: 100vw;
 }

 .title {
  color: rgb(163, 8, 0);
  font-family: 'tormenta';
  font-size: 4em;
  font-weight: normal;
  text-shadow: -2px 2px 1px rgb(68, 1, 0),
    -2px -2px 1px rgb(68, 1, 0),
    2px 2px 1px rgb(68, 1, 0),
    2px -2px 1px rgb(68, 1, 0),
    -3px 3px 2px rgb(248, 232, 202),
    -3px -3px 2px rgb(248, 232, 202),
    3px 3px 2px rgb(248, 232, 202),
    3px -3px 2px rgb(248, 232, 202);
 }
</style>
