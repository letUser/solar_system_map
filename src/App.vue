<template>
  <div id="app">
    <Header />
    <Map />
  </div>
</template>

<script>
import Header from "./components/header.vue";
import Map from "./components/map.vue";

export default {
  name: "App",
  components: {
    Header,
    Map
  }
};
</script>

<style>
body {
  margin: 0;
  /* background: url(./assets/space.jpg) no-repeat fixed; */
  background-size: cover;
  background-color: #000000;
  position: fixed;
  overflow: hidden;
  width: 100vw;
  height: 100vh;
  display: block;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
