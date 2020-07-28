<template>
  <div id="app">
    <MyName msg="Olatunji Omogbemile" />
  </div>
</template>

<script>
import MyName from "./components/MyName.vue";

export default {
  name: "App",
  components: {
    MyName,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  font-size: 80px;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
