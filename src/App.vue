<template>
  <div id="app">
    <GiphyDropdown />
  </div>
</template>

<script>
import GiphyDropdown from "./components/GiphyDropdown.vue";

export default {
  name: "App",
  components: {
    GiphyDropdown,
  },
};
</script>
<style scoped>
#app {
  padding: 8px;
}
</style>
