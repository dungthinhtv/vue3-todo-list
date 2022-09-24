<template>
  <div id="app">
    <Header />
    <Todos />
  </div>
</template>

<script>
import Header from './components/Header';
import Todex from './components/Todex';
export default {
  name: 'App',
  components: { Header, Todex },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
}
</style>
