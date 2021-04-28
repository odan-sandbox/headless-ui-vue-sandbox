<template>
  <TryMenu />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TryMenu from "./components/try-menu.vue";

export default defineComponent({
  name: "App",
  components: {
    TryMenu,
  },
});
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
