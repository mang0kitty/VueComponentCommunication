<template>
  <li class="list-group-item" style="cursor: pointer" @click="selectServer">Server {{server.id}}</li>
</template>

<script>
import { serverBus } from "../../main.js";
export default {
  props: ["server"], //prop set from outside from servers wher I pass server
  methods: {
    selectServer: function() {
      serverBus.selectServer(this.server);
    }
  }
};
</script>

<style scoped>
</style>