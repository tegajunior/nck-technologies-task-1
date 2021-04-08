<template>
  <div id="app">
    <div id="nav">
      <Navigation />
    </div>
    <router-view/>
  </div>
</template>

<script>
import Navigation from '@/components/Navigation.vue'
export default {
  name: "App",
  components: {
    Navigation,
  }
}
</script>

<style lang="scss">
  @import "node_modules/bootstrap/scss/bootstrap";
    .mpadding-y-5 {
      padding: 3% 0 6% 0;
  }
  .nck-gray-1 {
    color: #BEC2CA;
  }
  .nck-small-text-1 {
    font-size: 9px;
  }
  #app {
    width: 95%;
    max-width: 100%;
  }
</style>
