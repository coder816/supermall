<template>
  <div id="app">
    <main-tab-bar />
  </div>
</template>

<script>
import MainTabBar from "@/components/content/MainTabBar";
import router from "@/router";

export default {
  name:'App',
  components: {
    MainTabBar,
    router
  }
}

</script>

<style>

</style>
