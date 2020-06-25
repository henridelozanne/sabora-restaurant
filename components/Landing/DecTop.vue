<template>
  <div class="deco deco-top"></div>
</template>

<script>
export default {
  name: 'DecTop'
}
</script>

<style scoped>
.deco-top {
  position: absolute;
  left: 70px;
  top: 50px;
  width: 80px;
  height: 80px;
  border-top: 1px dotted rgba(255,255,255,0.4);
  border-left: 1px dotted rgba(255,255,255,0.4);
  /* z-index: 10; */
}
</style>