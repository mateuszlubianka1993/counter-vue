<template>
  <div class="counter">
    <h1>{{ value }}</h1>
   
  </div>
</template>

<script>
export default {
  name: 'Counter',
  props: {
    value: Number
  }
}
</script>

<style scoped>
 .counter {
   padding: 25px;
   border: 2px solid #4E7A48;
   color: #4E7A48;
   -webkit-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
   -moz-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
   box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
 }
</style>
