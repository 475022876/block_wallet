<template>
<div>
  <nut-tabbar @tab-switch="tabSwitch">
  <nut-tabbar-item tab-title="首页" icon="home"></nut-tabbar-item>
  <nut-tabbar-item tab-title="分类" icon="category"></nut-tabbar-item>
  <nut-tabbar-item tab-title="发现" icon="find"></nut-tabbar-item>
  <nut-tabbar-item tab-title="购物车" icon="cart"></nut-tabbar-item>
  <nut-tabbar-item tab-title="我的" icon="my"></nut-tabbar-item>
</nut-tabbar>
</div>
  
</template>

<script>
import { createApp } from 'vue';
// vue
import { Tabbar,TabbarItem,Icon } from '@nutui/nutui';
const app = createApp();
app.use(Tabbar,TabbarItem,Icon);
export default{
  name: 'App'
}
</script>

<style>
#app {
}
</style>
