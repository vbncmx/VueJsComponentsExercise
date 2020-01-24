<template>
  <div class="row">
    <div class="col-xs-12 col-sm-6">
      <ul class="list-group">
        <server-li v-for="id in count" :key="id" :id="id"></server-li>
      </ul>
    </div>
    <info></info>
  </div>
</template>

<script>
import Info from "./Info.vue";
import ServerLi from "./ServerLi.vue";

export default {
  data() {
    return {
      count: 10
    };
  },
  components: {
    "server-li": ServerLi,
    info: Info
  }
};
</script>