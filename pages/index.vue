<template>
  <div class="home">
    <div class="carousel">
      <Blanner></Blanner>
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
