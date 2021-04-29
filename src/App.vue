<template>
  <TryMenu />
  <TryListbox />
  <TryDialog />
</template>

<script lang="ts">
import { defineComponent } from "vue";
import TryMenu from "./components/try-menu.vue";
import TryListbox from "./components/try-listbox.vue";
import TryDialog from "./components/try-dialog.vue";

export default defineComponent({
  name: "App",
  components: {
    TryMenu,
    TryListbox,
    TryDialog,
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
