<template>
  <div id="app">
    <Header />
    <div class="container buttons-container">
      <div class="ui buttons">
        <button class="ui button" @click="counterValue--">Decrease</button>
        <div class="or"></div>
        <button class="ui positive button" @click="counterValue++">Increase</button>
      </div>
    </div>
    <Counter :value="counterValue"/>
  </div>
</template>

<script>
import Counter from './components/Counter.vue';
import Header from './components/Header';

export default {
  name: 'App',
  components: {
    Counter,
    Header
  },
  data: function() {
    return {
      counterValue: 0
    }
  }
}
</script>

<style>
body {
  background-color: #AAD671;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: #F0ED9E;
  width: 80%;
  margin: auto;
  padding-bottom: 100px;
}
.buttons-container {
  padding: 30px;
  -webkit-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
  -moz-box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
  box-shadow: 10px 10px 5px 0px rgba(0,0,0,0.75);
  margin-bottom: 25px;
}
</style>
