<template>
  <div id="app">
    <header-bg/>
  </div>
</template>

<script>
import HeaderBg from "./components/HeaderBg";

export default {
  name: "app",
  components: {
    HeaderBg
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
