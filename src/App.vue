<template>
  <div class="container">
    <header-cmp></header-cmp>
    <hr />
    <server-list></server-list>
    <hr />
    <footer-cmp></footer-cmp>
  </div>
</template>

<script>
import Header from "./Header.vue";
import Footer from "./Footer.vue";
import ServerList from "./ServerList.vue";

export default {
  components: {
    "server-list": ServerList,
    "header-cmp": Header,
    "footer-cmp": Footer
  }
};
</script>
