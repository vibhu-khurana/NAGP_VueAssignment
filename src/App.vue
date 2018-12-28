<template>
  <div id="app">
    <NavBar></NavBar>
    <router-view/>
    <NavFooter></NavFooter>
  </div>
</template>
<script>
import NavBar from "@/components/NavBar.vue";
import NavFooter from "@/components/NavFooter.vue";

export default {
  components: {
    NavBar, NavFooter
  }
};
</script>

<style>

</style>
