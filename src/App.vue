<template>
  <div id="app">
    <router-view />
    <main-tab-bar />
  </div>
</template>

<script>
import MainTabBar from "@/components/content/MainTabBar";

export default {
  name:'App',
  components: {
    MainTabBar
  }
}

</script>

<style>
  body {
    padding: 0;
    margin: 0;
  }
</style>
