<template>
  <TabBar>
    <TabBarItem path="/home" col="green">
      <div slot="icon" class="fa fa-home item-icon" ></div>
      <div slot="text">首页</div>
    </TabBarItem>
    <TabBarItem path="/category" col="green">
      <div slot="icon" class="fa fa-th-large item-icon" ></div>
      <div slot="text">分类</div>
    </TabBarItem>
    <TabBarItem path="/shoppingCart" col="green">
      <div slot="icon" class="fa fa-shopping-cart item-icon" ></div>
      <div slot="text">购物车</div>
    </TabBarItem>
    <TabBarItem path="/profile" col="green">
      <div slot="icon" class="fa fa-user item-icon" ></div>
      <div slot="text">我的</div>
    </TabBarItem>
  </TabBar>
</template>

<script>
  import TabBar from "../common/tabbar/TabBar"
  import TabBarItem from "../common/tabbar/TabBarItem"
  export default {
    name: "",
    components : {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>
  .tab-bar-item .item-icon{
    font-size: 26px;
  }
</style>