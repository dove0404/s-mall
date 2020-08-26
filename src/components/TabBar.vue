<template>
  <div id="s-mall-tabbar">
    <div class="s-mall-item"><i></i><span>首页</span></div>
    <div class="s-mall-item"><i></i><span>分类</span></div>
    <div class="s-mall-item"><i></i><span>购物车</span></div>
    <div class="s-mall-item"><i></i><span>我的</span></div>
  </div>
</template>

<style scoped>
#s-mall-tabbar{
  display: flex;
  background-color: aquamarine;
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
}
.s-mall-item{
  flex: 1;
  text-align: center;
  border: 1px solid #666;
  height: 49px;
}
.s-mall-item i{
  display: block;
  height: 20px;
  width: 20px;
  background-color: blueviolet;
}
</style>
