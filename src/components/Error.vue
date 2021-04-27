<!--
 * @Description: 
 * @Author: Jungle
 * @Date: 2020-02-27 13:57:14
 * @LastEditors: Jungle
 * @LastEditTime: 2020-02-27 14:11:31
 -->
<template>
  <div class="error">
    <div class="main"></div>
    <el-button type="primary" round @click="goAbout">返回介绍页</el-button>
  </div>
</template>
<script>
export default {
  methods: {
    goAbout() {
      this.$router.replace({ path: "/about" });
    },
  },
};
</script>
<style scoped>
.error {
  height: 530px;
  width: 1225px;
  margin: 0 auto;
}
.error .main {
  margin: 0 362.5px;
  height: 500px;
  background: url(../assets/imgs/error.png) no-repeat;
}
.error .el-button {
  /* color: red; */
  display: block;
  margin: 0 auto;
}
</style>