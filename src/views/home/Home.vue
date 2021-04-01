<template>
  <div id="home">
   <nav-bar></nav-bar>
  </div>
</template>

<script>
  import NavBar from "components/common/navbar/NavBar";
  export default {
    name:"Home",
    components:{
      NavBar
    }
 }
</script>

<style scoped>
  #home {
    height: 100vh;
    position: relative;
  }

 /* .home-nav {
    background-color: var(--color-tint);
    color: #fff;
    position: relative;
    z-index: 9;
  }

  .tab-control {
    position: relative;
    z-index: 9;
  }

  .content {
    position: absolute;
    top: 44px;
    bottom: 49px;
    left: 0;
    right: 0;
  }*/
</style>
