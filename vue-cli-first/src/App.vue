<template>
  <div id="app">
    <MainTitle />
    <MainHero />
  </div>
</template>

<script>
import MainTitle from "./components/MainTitle.vue";
import MainHero from "./components/MainHero.vue";

export default {
  name: "App",
  components: {
    MainTitle,
    MainHero,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
