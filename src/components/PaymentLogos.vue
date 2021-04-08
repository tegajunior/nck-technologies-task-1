<template>
  <div>
    <div class="d-flex justify-content-between align-items-center">
       <div class="flex-item-logo-container">
           <img src="../assets/visa1.png" alt="Visa Logo">
       </div>
       <div class="flex-item-logo-container">
           <img src="../assets/discover1.jpg" alt="Discover Logo">
       </div>
       <div class="flex-item-logo-container">
           <span>&nbsp;</span>
       </div>
       <div class="flex-item-logo-container">
           <img src="../assets/paypal1.png" alt="Paypal Logo">
       </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "PaymentLogos",
}
</script>

<style scoped>
  .flex-item-logo-container img {
      width: 40px;
  }
  /* .flex-item-logo-container img:last-child {
      width: 80px;
  } */

</style>