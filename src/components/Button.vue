<template>
    <div>
        <button>{{ text }}</button> 
    </div>
</template>

<script>
export default {
  name: "Button",
  props: ["text"],
}
</script>

<style scoped>
   button {
    font-weight: 500;
    border-radius: 3px;
    padding-top: 10px;
    padding-bottom: 10px;
    color: #fff;
    background-color: #3F67E9;
    border: 0;
     width: 100%;
   }
</style>