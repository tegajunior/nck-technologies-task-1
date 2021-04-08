<template>
  <div>
     <form action="#">
        <div class="row align-items-end">
            <div class="form-group col-md-5">
                <label class="form-control-label" for="creditCardNumber">Credit card number</label>
                <input type="text" id="creditCardNumber" class="form-control" value="4478 0007 0879 0016">
            </div>
            <div class="form-group col-md-5">
                <label class="form-control-label" for="expirationDate">Expiration date</label>
                <input type="text" id="expirationDate" class="form-control" value="04/25">
            </div>
        </div>
        <div class="row align-items-end">
            <div class="form-group col-md-5">
                <label class="form-control-label" for="securityCode">Security code</label>
                <input type="text" id="securityCode" class="form-control" value="409">
            </div>
            <div class="form-group col-md-5">
                <label class="form-control-label" for="postalCode">Postal Code</label>
                <input type="text" id="postalCode" class="form-control" value="10134">
            </div>
        </div>
        <div class="form-group">
          <div class="form-check">
            <label for="useNextTime" class="form-check-label">
              <input type="radio" value="yes" checked id="useNextTime" class="form-check-input">Use this card for next time purchase
            </label>
          </div> 
        </div>
        <div class="row"> 
            <div class="form-group mx-auto col-12">
               <Button :text="'Add card'"/>
            </div>
        </div>
     </form>     
  </div>
</template>

<script>
import Button from '@/components/Button.vue'
export default {
  name: "AddCardForm",
  components: {
      Button,
  }
}
</script>

<style scoped>
  label {
      font-weight: 500;
  }
  input[type=text], input[type=password] {
    background-color: #F0F1F3;
  }
</style>