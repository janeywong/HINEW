<template>
  <el-container>
    <el-main>
      <router-view />
    </el-main>
  </el-container>
</template>

<style lang="less" scoped>
.el-container {
  height: 100%;
}

.el-main {
  --el-main-padding: 0px;

  position: relative;
  overflow: hidden;
}
.el-header {
  --el-header-padding: 0 12px;
  position: relative;
  z-index: 3;
  background-color: #fff;

  &:after {
    position: absolute;
    bottom: 0;
    left: 0;
    width: 100%;
    height: 1px;
    background-color: #e5e5e5;
    content: "";
  }
}
</style>
<script setup lang="ts">
</script>
