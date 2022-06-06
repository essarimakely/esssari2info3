<script setup>
import HeaderComp from "@/components/template/HeaderComp.vue";
import RodapeComp from "@/components/template/RodapeComp.vue";
</script>

<template>
  <HeaderComp></HeaderComp>
  <RouterView />
  <RodapeComp></RodapeComp>
</template>
<style>
@import "@/assets/base.css";

#app {
  max-width: 1280px;
  margin: 0 auto;
  padding: 2rem;
  height: 100vh;

  font-weight: normal;
}

a {
  color: inherit;
  text-decoration: none;
}
footer {
  height: 15%;
  background-color: rgb(57, 57, 128);
  color: white;
  font-size: 1.3rem;
  display: flex;
  align-items: center;
  padding-left: 20px;
  justify-content: space-between;
  padding-left: 20px;
}
header span {
  padding: 0 20px;
  padding-right: 20px;
}
main {
  height: 80%;
}
</style>
