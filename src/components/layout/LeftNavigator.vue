<template>
  <Menu theme="light" width="auto" style="text-align:center;">
    <Submenu>
      <template #title>
        <Icon type="ops-navigate"></Icon>
        功能列表
      </template>
      <MenuItem name="1-1">
        <router-link to="/">首頁</router-link>
      </MenuItem>
      <MenuItem name="1-2">
        <router-link to="/Information">個人資訊</router-link>
      </MenuItem>
      <MenuItem name="1-3">
        <router-link to="/Hello">HelloWorld測試</router-link>
      </MenuItem>
      <MenuItem name="1-4">
        <router-link to="/ProductList">商品列表</router-link>
      </MenuItem>
    </Submenu>
  </Menu>
</template>

<script>
export default {
};
</script>

<style>
</style>