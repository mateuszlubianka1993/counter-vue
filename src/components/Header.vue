<template>
  <h2 class="ui icon header-container">
  <img alt="Vue logo" src="../assets/logo.png">
  <div class="content">
    <h1>Counter App</h1>
    <div class="sub header">Click and increase or decrease number</div>
  </div>
</h2>
</template>

<script>
export default {
  name: 'Header',
  props: {
    
  }
}
</script>

<style scoped>
  .header-container {
    padding: 25px;
    border-bottom: 2px solid #4E7A48;
    -webkit-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
    -moz-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
    box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
  }
</style>
