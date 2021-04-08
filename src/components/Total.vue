<template>
  <div>
    Total: &#8358; {{ total}}   
  </div>
</template>

<script>
export default {
 name: "Total",
 props: {
    total: {
     type: String,
     default: '0000.000',
    },
 },
};
</script>
<style scoped>
    div {
        font-weight: 800;
        font-size: 18px;
    }
</style>