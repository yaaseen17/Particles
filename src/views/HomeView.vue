<template>
  <div class="landing">
    <div class="particles">
      <Particles />
    </div>
    <div class="header">
      <h1>Yaaseen Davids</h1>
      <h2>Full stack Developer</h2>
    </div>
  </div>
</template>

<script>
import Particles from "../components/Particles.vue";
export default {
  name: "HomeView",
  components: {
    Particles,
  },
};
</script>
<style scoped>
.home {
  height: 100vh;
}
.particles {
  z-index: -1;
}
.header h2 {
  color: white;
  font-family: "Bitter", serif;
}
.header h1 {
  color: white;
  font-family: "Bitter", serif;
}
.header {
  position: absolute;
  top: 50%;
  left: 35%;
  padding: 10px;
  background-color: rgb(0, 0, 0, 0.8);
  border-radius: 10px;
}
</style>
