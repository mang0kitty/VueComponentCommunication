<template>
  <div class="col-xs-12 col-sm-6">
    <ul class="list-group">
      <appServer v-for="server in servers" :key="server.id" :server="server"></appServer>
    </ul>
  </div>
</template>

<script>
import Server from "./Server.vue";
export default {
  data: function() {
    return {
      servers: [
        { id: 1, status: "Running" },
        { id: 2, status: "Running" },
        { id: 3, status: "Running" },
        { id: 4, status: "Running" }
      ]
    };
  },
  components: {
    appServer: Server
  }
};
</script>

<style>
</style>
