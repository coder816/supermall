<template>
  <div id="home">
    <nav-bar>
      <template v-slot:nav-left></template>
      <template v-slot:nav-center><h2>首页</h2></template>
      <template v-slot:nav-right></template>
    </nav-bar>
  </div>
</template>

<script>
import NavBar from "@/components/common/navbar/NavBar";

export default {
  name: "Home",
  components: {
    NavBar
  }
}
</script>

<style scoped>

</style>