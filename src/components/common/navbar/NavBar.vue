<template>
<div class="nav-bar">

  <div class="left"><slot></slot></div>
  <div class="center"><slot></slot></div>
  <div class="right"><slot></slot></div>

</div>
</template>

<script>
  export default {
    name:"NavBar"
  }
</script>

<style>
 .nav-bar {
   display: flex;
   height: 44px;
   line-height: 44px;
 }
  .left, .right {
    width: 60px;
    background-color: red;
  }
  .center {
    flex: 1;
    background-color: blue;
  }
</style>
