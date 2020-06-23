<template>
  <div class="top-nav">
    <nuxt-link to="#">
      <span>Call now:</span>
      +33123456789
    </nuxt-link>
    <nuxt-link to="#">
      <span>Email us:</span>
      jorge@sabora.com
    </nuxt-link>
  </div>
</template>

<script>
export default {
  name: 'TopNavbar'
}
</script>

<style>
.top-nav {
  display: flex;
  justify-content: flex-end;
}
</style>