<template>
  <div id="app">
    <Navbar />

    <Todos />
  </div>
</template>

<script>
import Navbar from './components/Navbar';

import Todos from './components/Todos';

export default {
  name: 'App',
  components: { Todos, Navbar },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: rgb(219, 219, 219);
  margin: 20px auto;
  width: 90%;
  max-width: 800px;
}
</style>
