<template>
  <div class="home">
    <!-- Navigation is Here Already -->
    <div class="row px-4 pt-2 justify-content-between align-items-center">
      <div class="col-12 col-md-5">
        <h6>Payment Information</h6>
        <p class="nck-gray-1 nck-small-text-1">Choose your method of payment</p>
      </div>
      <div class="col-12 col-md-2">
        <PaymentLogos />
      </div>
    </div>
    <div class="row px-4 pt-3 justify-content-between align-items-center">
        <div class="col-12 col-md-5 mb-4">
           <MasterCard />
        </div>
        <div class="col-md-5">
          <AddCardForm />
        </div>
    </div>
    <HorizontalRule />
    <div class="row px-4 pt-2">
      <div class="col-sm-12">
      <Checkout
        :subtotal="'2,497.00'"
        :tax="'119.64'"
        :promo_cash="'60.00'"
      />
      </div>
    </div>
    <HorizontalRule />
    <div class="row px-4 py-3 justify-content-between align-items-center">
      <div class="col-sm-12 col-md-2 mb-md-0 mb-3">
        <Button :text="'Complete payment'"/>
      </div>
      <div class="col-sm-12 col-md-4 text-center text-md-right">
        <Total :total="'2556.64'"/>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from '@/components/HelloWorld.vue'
import HorizontalRule from '@/components/HorizontalRule.vue'
import PaymentLogos from '@/components/PaymentLogos.vue'
import MasterCard from '@/components/MasterCard.vue'
import AddCardForm from '@/components/AddCardForm.vue'
import Checkout from '@/components/Checkout.vue'
import Button from '@/components/Button.vue'
import Total from '@/components/Total.vue'

export default {
  name: 'Home',
  components: {
    //HelloWorld
    HorizontalRule,
    PaymentLogos,
    MasterCard,
    AddCardForm,
    Checkout,
    Button,
    Total
  }
}
</script>

