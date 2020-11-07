<template>
  <div id="tab-bar">
    <slot></slot>
  </div>
</template>

<script>
  export default {
    name: ""
  }
</script>

<style scoped>
  #tab-bar{
    position: fixed;
    height: 55px;
    bottom: 0px;
    left: 0px;
    right: 0px;
    display: flex;
    text-align: center;
    background: #ccc;
  }

</style>