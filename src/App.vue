<template>
  <Navbar />
  <section class="Home">
    <HomeView />
  </section>
</template>
<script>
import Navbar from "./components/Navbar.vue";
import HomeView from "./views/HomeView.vue";
export default {
  data() {
    return {};
  },
  components: {
    Navbar,
    HomeView,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  margin: 0%;
  padding: 0%;
  background-color: rgb(38, 37, 37);
}

body {
  background: black;
}
</style>
