<script></script>

<template>
  <header> 
    <span class="texto-header">Home</span>
    <span class="separador">|</span> 
    <span class="texto-header">Jogadores</span>
    <span class="separador">|</span>
    <span class="texto-header">Times</span>

  <main>Main</main>
  <footer>Rodapé</footer>
</template>

<style>
@import "@/assets/base.css";

#app {
  max-width: 100%;
  margin: 0 auto;
  /* padding: 2rem; */
  height: 100vh;

  font-weight: normal;
}

header,
footer {
  background-color: rgb(0, 114, 28);
  height: 15%;
  font-size: 1.3rem;
  color: white;
  display: flex;
  align-items: center;
  padding-left: 2%;
}
main {
  min-height: 70%;
  padding-left: 2%;
}
header span{
  padding: 0 10px;
}
</style>
