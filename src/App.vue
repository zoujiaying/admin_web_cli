<script setup lang="ts">
// This starter template is using Vue 3 <script setup> SFCs;
// Check out https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup;
import zhCn from 'element-plus/lib/locale/lang/zh-cn'
</script>

<template>
  <el-config-provider :locale="zhCn">
    <router-view />
  </el-config-provider>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

* {
  margin: 0;
  padding: 0;
}

ul,
li {
  list-style: none;
}
</style>
