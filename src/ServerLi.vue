<template>
  <li class="list-group-item">Server #{{ id }}</li>
</template>

<script>
export default {
  data() {
    return {
      id: 0
    };
  },
  props: ["id"]
};
</script>