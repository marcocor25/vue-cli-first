<template>
  <div id="app">
    <newTitle />
    <heroJumbo />
  </div>
</template>

<script>
import newTitle from "./components/newTitle.vue";
import heroJumbo from "./components/heroJumbo.vue";

export default {
  name: "App",
  components: {
    newTitle,
    heroJumbo,
  },
};
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

#app {
  height: 100vh;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background: #333;
}
</style>
