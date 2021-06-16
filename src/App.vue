<template>
  <Nav />

  <ScrollingHeader />
</template>

<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import ScrollingHeader from "./components/ScrollingHeader.vue";
import Nav from "./components/Nav.vue";

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;

  color: black;
  margin: 0px;
  padding: 0px;
  box-sizing: border-box;
}
body {
  background: whitesmoke;
}
</style>
