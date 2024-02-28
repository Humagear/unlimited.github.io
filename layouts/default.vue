<template>
  <el-container>
    <el-header>
<!--      上部导航栏-->
      <Head></Head>
    </el-header>

    <el-main >
<!--      具体内容-->
      <nuxt></nuxt>
    </el-main>
    <el-footer>Footer</el-footer>
  </el-container>

</template>

<script>
import Head from "~/components/comon/head.vue";
export default {
  name: "Default",
  components:{
    Head
  }
}
</script>

<style scoped>

* {
  padding: 0;
  margin: 0;
}



</style>
