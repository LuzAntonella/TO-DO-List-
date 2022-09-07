<template>
  <div id="app">
    <Lista />
  </div>
</template>

<script>
import Lista from "./components/Lista.vue";
export default {
  name: "App",
  components: {
    Lista,
  },
};
</script>

<style>
#app {
  max-width: 480px;
  width: 100%;
  max-height: 100%;
  background-color: rgb(255, 255, 255);
  padding: 25px;
  border-radius: 25px;
  /*overflow: auto;*/
  /*color: #222;*/
}
</style>
