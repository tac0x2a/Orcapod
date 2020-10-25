<template>
<div class="home">
  <v-container>
    <h1>Hello,Orcapod</h1>
    <v-img
      lazy-src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Orca_pod_southern_residents.jpg?1603612317771"
      max-height="450"
      max-width="450"
      src="https://upload.wikimedia.org/wikipedia/commons/9/9f/Orca_pod_southern_residents.jpg?1603612317771"
    ></v-img>
  </v-container>
</div>
</template>

<script lang="ts">
import Vue from "vue";
import HelloWorld from "./components/HelloWorld.vue";

export default Vue.extend({
  name: "OrcapodSample",

  components: {},

  data: () => ({
    //
  })
});
</script>

<style>

</style>