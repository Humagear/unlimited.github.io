<template>
  <div class="home">
    <div class="carousel">
<!--      轮播图-->
      <Blanner></Blanner>
    </div>
    <div class="content">
<!--      宣传广告部分-->
    </div>
  </div>



</template>

<script lang="ts">
import Vue from 'vue'
import Blanner from "~/components/comon/blanner.vue";
export default Vue.extend({
  name: 'IndexPage',
  components:{
    Blanner
  }
})
</script>
