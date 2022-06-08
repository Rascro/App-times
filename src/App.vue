<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue";
import FooterComp from "@/components/template/FooterComp.vue";
</script>

<template>
  <HeaderComp />
  <main>
    <RouterView />
  </main>
  <FooterComp />
</template>

<style>
@import url("https://fonts.googleapis.com/css2?family=Cormorant+Garamond&display=swap");

#app {
  max-width: 1280px;
  margin: 0 auto;
  height: 97vh;
  font-weight: normal;
  font-family: "Cormorant Garamond", serif;
}

main {
  height: 78%;
}

a {
  color: inherit;
  text-decoration: none;
}

.router-link-active {
  color: rgb(17, 206, 0);
}
</style>
