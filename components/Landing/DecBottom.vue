<template>
  <div class="deco deco-bottom"></div>
</template>

<script>
export default {
  name: 'DecBottom'
}
</script>

<style>
.deco-bottom {
  position: absolute;
  bottom: 50px;
  left: 70px;
  width: 80px;
  height: 80px;
  border-bottom: 1px dotted rgba(255,255,255,0.4);
  border-left: 1px dotted rgba(255,255,255,0.4);
  z-index: 10;
}
</style>