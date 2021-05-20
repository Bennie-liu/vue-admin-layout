<template>
  <div class="app-container">
    <Asider />
    <div class="main-container">
      <Header />
      <div class="app-main">
        <Mainer />
      </div>
    </div>
  </div>
</template>

<script>
import Asider from "./Views/Layout/Asider.vue";
import Header from "./Views/Layout/Header.vue";
import Mainer from "./Views/Layout/Mainer.vue";

export default {
  name: "App",
  components: {
    Asider,
    Header,
    Mainer,
  },
};
</script>

<style>
.app-container {
  width: 100vw;
  height: 100vh;
  display: flex;
}
.main-container {
  flex-grow: 1;
}
.app-main {
  height: calc(100vh - 66px);
  overflow: auto;
  background-color: #f6f8f9;
  width: 100%;
}
</style>
