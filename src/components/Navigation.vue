<template>
  <div class="mpadding-y-5 pl-2 pr-0">
      <nav class="navbar navbar-light navbar-expand-md justify-content-start justify-content-md-center justify-content-lg-end">
        <!-- <button class="navbar-toggler" type="button"
          data-toggle="collapse"
          data-target="#myTogglerNav"
          aria-controls="myTogglerNav"
          aria-expanded="false"
          aria-label="Toggle-navigation" 
          ><span class="navbar-toggler-icon"></span></button> -->
        <!-- <div class="collapse navbar-collapse" id="myTogglerNav"> -->
          <div class="navbar-nav">
            <a class="nav-item nav-link" href="#">TRIPS</a>
            <a class="nav-item nav-link" href="#">RECENTLY VIEWED</a>
            <a class="nav-item nav-link" href="#">BOOKINGS</a>
          </div>
        <!-- </div> -->
          <a class="nav-item nav-link mt-0 mt-n4 ml-auto ml-md-0"><img alt="Profile Photo" src="../assets/profile-pic.png"></a>
      </nav>
      <HorizontalRule />
  </div>
</template>

<script>
import HorizontalRule from '@/components/HorizontalRule.vue'
export default {
  name: "Navigation",
  components: {
    HorizontalRule,
  }
}
</script>
<style scoped>
  .nav-link {
    color: black;
    font-size: 13px;
    font-weight: 800;
  }
</style>