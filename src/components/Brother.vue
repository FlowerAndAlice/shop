<template>
  <div class="hello">
    <h1>up池</h1>
    <h3>{{state.message}}</h3>
    <button @click="pray">抽卡</button>
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
        str: '枫原万叶 x 1 !'
      }
    },
    methods: {
      pray() {
        store.setMessage(this.str);
      }
    }
  }
</script>

<style scoped>

</style>