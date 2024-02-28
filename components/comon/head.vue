<template>
  <div class="header" >
    <div class="logo">
      <img src="">
    </div>
    <div class="useLink">

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
    background: antiquewhite;
    display: flex;
    justify-content: center;
  }
  .logo {
    position: relative;
    right: 20%;
  }
  .useLink {
    position: relative;
    left: 20%;
  }

</style>
