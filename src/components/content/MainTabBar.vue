<template>
  <tab-bar>
    <TabBarItem path="/home" activeColor="#f86401">
      <template v-slot:item-icon><img src="~assets/img/tabbar/home.svg" alt=""></template>
      <template v-slot:item-icon-active><img src="~assets/img/tabbar/home-active.svg" alt=""></template>
      <template v-slot:item-text><div>首页</div></template>
    </TabBarItem>
    <TabBarItem path="/category" activeColor="#f86401">
      <template v-slot:item-icon><img src="~assets/img/tabbar/category.svg" alt=""></template>
      <template v-slot:item-icon-active><img src="~assets/img/tabbar/category-active.svg" alt=""></template>
      <template v-slot:item-text><div>分类</div></template>
    </TabBarItem>
    <TabBarItem path="/shopcart" activeColor="#f86401">
      <template v-slot:item-icon><img src="~assets/img/tabbar/shopcart.svg" alt=""></template>
      <template v-slot:item-icon-active><img src="~assets/img/tabbar/shopcart-active.svg" alt=""></template>
      <template v-slot:item-text><div>购物车</div></template>
    </TabBarItem>
    <TabBarItem path="/profile" activeColor="#f86401">
      <template v-slot:item-icon><img src="~assets/img/tabbar/profile.svg" alt=""></template>
      <template v-slot:item-icon-active><img src="~assets/img/tabbar/profile-active.svg" alt=""></template>
      <template v-slot:item-text><div>我的</div></template>
    </TabBarItem>
  </tab-bar>
</template>

<script>
import TabBar from "@/components/common/tabbar/TabBar";
import TabBarItem from "@/components/common/tabbar/TabBarItem";

export default {
  name: "MainTabBar",
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style scoped>
  img{
    height: 24px;
    width: 24px;
    margin-top: 3px;
    vertical-align: middle;
    margin-bottom: 1px;
  }
</style>
