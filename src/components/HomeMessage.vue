<template>
  <div class="home-box">
    <img class="home-img" alt="Tormenta" src="../assets/Tormenta.png">
    <p class="home-txt">
      Bem vindo a <span class="spotlight">Fábrica de Ameaças de Arton</span> um projeto para auxiliar na criação de ameaças para o RPG de mesa <span class="spotlight">Tormenta 20</span>.
    </p>
    <p class="home-txt">
      Para todos que já jogaram Tormenta 20 e se aventuraram por Arton, sabem que essa terra fantástica é repleta dos mais diversos tipos de perigos, mas mesmo assim, as vezes nos surge uma ideia que parece não se encaixar em nenhuma das varias ameaças já existentes, e então o que nos resta é utilizar a nossa criatividade para dar forma a nossas ideias.
    </p>
    <p class="home-txt">
      O processo criar uma nova ameaça por vezes pode ser trabalhoso e a ideia por trás deste projeto é exatamente reduzir um pouco deste trabalho.
    </p>
    <p class="home-txt">
      Sendo assim, espero que aproveite a ferramenta e tenha uma boa experiencia.
    </p>
  </div>
</template>

<script>
export default {
  name: 'HomeMessage'
}
</script>

<style scoped>

.home-box {
  background-image: url('../assets/PageBG.svg');
  background-size: cover;
  border-radius: 50px;
  box-shadow: 20px 20px 60px rgb(217, 217, 217),
    -20px -20px 60px rgb(255, 255, 255);
  height: fit-content;
  margin: 2vb;
  min-height: 900px;
  width: 45vw;
}

.home-img {
  margin: 2.5vb;
  max-width: 300px;
  width: 50%;
}

.home-txt {
  background-color: rgba(255, 255, 255, 0.7);
  color: rgb(68, 2, 0);
  font-size: 1.3em;
  padding: 1.5vb;
  text-align: center;
}

.spotlight {
  color: rgb(168, 20, 0);
  font-family: 'Tormenta'
}
</style>
