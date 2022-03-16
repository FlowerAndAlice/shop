<template>
  <div id="app">
    <Header></Header>
  </div>
</template>

<script>
  import Header from "./components/Header/Header.vue";
  export default {
    components: {
      Header
    },
    data() {
      return {
        pray: "",
        prayList: [],
      }
    },
    methods: {

    },
  }
</script>

<style>
  * {
    color: pink;
    list-style: none;
  }
  
  body {
    background-image: url(https://pic.imgdb.cn/item/61113d075132923bf8b88fb2.jpg);
    background-size: cover;
  }
</style>