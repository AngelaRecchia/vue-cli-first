<template>
  <div id="app">
    <Title/>
    <Hero/>
    
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero,
  },
};
</script>

<style>
  #app {
    font-family: Arial, Helvetica, sans-serif;
    background-color: #F9F9F9;
    height: 100vh;
    overflow: hidden;
  }

  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
</style>