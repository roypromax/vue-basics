<template>
  <div id="app">
    <Heading />
    <Counter />
  </div>
</template>

<script>
import Heading from "./components/Heading.vue";
import Counter from "./components/Counter.vue";
export default {
  name: "App",
  components: {
    Heading,
    Counter,
  },
};
</script>

<style>
#app {
  font-family: Arial, Helvetica, sans-serif;
  text-align: center;
  margin-top: 40px;
}
</style>
