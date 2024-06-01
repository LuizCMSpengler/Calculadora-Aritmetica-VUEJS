<script>
import Calculadora from './components/Calculadora.vue';

export default {
  name: 'App',
  components: {
    Calculadora,
  },
};
</script>

<template>
  <div id="app">
    <Calculadora />
  </div>
</template>

<style>
input {
  max-width: 420px;
}

option {
  background-color: #b3e4e1c5;
}
</style>