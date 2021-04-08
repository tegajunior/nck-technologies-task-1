<template>
  <div>
     <div class="d-flex justify-content-between align-items-center">
        <div>Subtotal</div>
        <div>&#8358;{{ subtotal }}</div>
     </div>
     <div class="d-flex justify-content-between align-items-center">
        <div>Estimated TAX</div>
        <div>&#8358;{{ tax }}</div>
     </div>
     <div class="d-flex justify-content-between align-items-center">
        <div>Promotional code: <span>{{ promo_code }}</span></div>
        <div>&#8358;{{ promo_cash }}</div>
     </div>
  </div>
</template>

<script>
export default {
 name: "Checkout",
 props: {
    subtotal: {
      type: String,
      default: '0000.00'
    },
    tax: {
      type: String,
      default: '0000.00'
    },
    promo_code: {
      type: String,
      default: 'Z4KXLM9A'
    },
    promo_cash: {
    type: String,
    default: '0000.00'
    }
 }
}
</script>

<style scoped>
    div {
     font-weight: 500;
     font-size: 13px;
    }
    div span {
      color: #BEC2CA;
      font-weight: 400;
    }
</style>