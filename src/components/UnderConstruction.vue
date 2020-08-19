<script lang="ts">
import Vue from 'vue'
export default Vue.extend({});
</script>

<template>
  <div class="under-construction">
    <div class="under-construction__content">
      <h1>Under Construction</h1>
      <p>This site is currently undergoing a complete rewrite using the Vue framework.</p>
      <p>Please check back shortly.</p>
      <p>I am sorry for the inconvenience.</p>
    </div>
  </div>
</template>

<style lang="scss" scoped>
  .under-construction {
    height: 100vh;
    width: 100vw;

    &__content {
      display: flex;
      align-items: center;
      justify-content: center;
      flex-direction: column;
    }
  }
</style>