<template>
  <div id="app">
    <List />
  </div>
</template>

<script>
import List from "@/components/List.vue";

export default {
  components: { List },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
