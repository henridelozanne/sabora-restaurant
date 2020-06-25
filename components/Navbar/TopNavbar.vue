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

<style lang="scss">
.top-nav {
  display: flex;
  justify-content: flex-end;
  padding: 15px 0;
  font-size: 14px;

  a {
    text-decoration: none;
    color: white;

    span {
      font-weight: 800;
      margin-right: 5px;
    }
  }

  a:not(:first-of-type) {
    margin-left: 20px;
  }
}
</style>