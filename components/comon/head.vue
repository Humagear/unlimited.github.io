<template>
  <div class="header justify-around" >
    <div class="logo ">
      <img src="assets/images/bds_qzone.png">
    </div>
    <div class="title">
      这是标题
    </div>
    <div class="useLink ">
      <el-menu mode="horizontal" class="elMenu mx-32px ">
        <el-menu-item >
          <nuxt-link to="/" class="mx-32px">首页</nuxt-link>
        </el-menu-item>
        <el-menu-item>
          <nuxt-link to="/about" class="mx-32px">关于我们</nuxt-link>
        </el-menu-item>
        <el-menu-item>
          <nuxt-link to="/serve" class="mx-32px">主营业务</nuxt-link>
        </el-menu-item>
        <el-menu-item>
          <nuxt-link to="/contact" class="mx-32px">联系我们</nuxt-link>
        </el-menu-item>
      </el-menu>
    </div>
  </div>
</template>

<script>
export default {
  name: "headerNav"
}
</script>

<style scoped>
 *{
   text-decoration: none;
 }
  .header {

    display: flex;
  }
  .title {
    position: relative;
    right: 20%;
  }



</style>
