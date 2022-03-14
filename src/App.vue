<template>
  <div id="app">
    <sister></sister>
    <brother></brother>
  </div>
</template>

<script>
  import sister from "./components/Sister.vue";
  import brother from "./components/Brother.vue";
  export default {
    components: {
      sister,
      brother,
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