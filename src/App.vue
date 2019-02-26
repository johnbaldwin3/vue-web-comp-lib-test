<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <TestWebComponent msg="Testing External Modules">Slot Test</TestWebComponent>
  </div>
</template>

<script>
import TestWebComponent from "./components/TestWebComponent.vue";

export default {
  name: "app",
  components: {
    TestWebComponent
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
  margin-top: 60px;
}
</style>
