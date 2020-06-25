<template>
  <div class="important-btn">
    <Play />
    <span>View promo video</span>
  </div>
</template>

<script>
import Play from '../SVGs/Play'

export default {
  name: 'ImportantButton',
  components: {
    Play
  }
}
</script>

<style lang="scss">
.important-btn {
  position: absolute;
  top: 50%;
  right: 0;
  width: 300px;
  z-index: 20;
  height: 50px;
  margin-top: -15px;
  display: flex;
  align-items: center;
  cursor: pointer;

  span {
    margin-left: 20px;
    color: white;
    font-style: italic;
  }
}
</style>