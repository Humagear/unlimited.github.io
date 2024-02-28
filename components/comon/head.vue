<template>
  <div class="header" >
    <div class="header-left ">
      <div class="logo mr-12">
        logo
      </div>
      <div class="title">
        title
      </div>
    </div>

    <div class="useLink ">
      <el-menu mode="horizontal">
        <el-menu-item>
          <nuxt-link to="/" class="mx-32px">首页</nuxt-link>
        </el-menu-item>
        <el-menu-item>
          <nuxt-link to="/about" class="mx-32px">关于我们</nuxt-link>
        </el-menu-item>
        <el-menu-item>
          <nuxt-link to="/serve" class="mx-32px">提供服务</nuxt-link>
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
    justify-content: center;
  }
  .header-left  {
    position: relative;
    right: 20%;
    display: flex;
    justify-items: baseline;
  }

  .useLink {
    position: relative;
    left: 20%;
  }

</style>
