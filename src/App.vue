<script lang="ts">
import Vue from "vue";
import UnderConstruction from "@/components/UnderConstruction.vue";

export default Vue.extend({
  name: "App",
  components: {
    "under-construction": UnderConstruction
  }
});
</script>

<template>
  <div id="app">
    <under-construction />
  </div>
</template>

<style lang="scss">
* {
  box-sizing: border-box;
  font-family: "Lucida Sans", "Lucida Sans Regular", "Lucida Grande",
    "Lucida Sans Unicode", Geneva, Verdana, sans-serif;
}

body {
  margin: auto;
}
</style>
