<script setup>
import HeaderComp from './components/template/HeaderComp.vue';
import FooterComp from './components/template/FooterComp.vue';
</script>
<template>
  <HeaderComp />
  <RouterView />
  <FooterComp />
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

a{
  color: inherit;
  text-decoration: none;
}

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
header span {
  padding: 0 10px;
}
</style>
