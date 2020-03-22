<template>
  <div id="app">
    <Header />
    <div class="containe">
      <div class="ui buttons">
        <button class="ui button">Decrease</button>
        <div class="or"></div>
        <button class="ui positive button">Increase</button>
      </div>
    </div>
    <Counter msg="Welcome to Counter App"/>
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
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
