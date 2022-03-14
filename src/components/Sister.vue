<template>
    <div class="hello">
      <h1>武器池</h1>
      <h3>{{state.message}}</h3>
    </div>
  </template>

<script>
  import store from "../store.js";
  export default {

    props: {

    },
    data() {
      return {
        state: store.state,
      }
    }
  }
</script>

<style scoped>

</style>