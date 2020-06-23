<template>
  <div class="container">
    <div class="hero">
      <h4>Quality food in a beautiful place</h4>
      <h2>Welcome to Sabora Restaurant</h2>
      <nuxt-link to="/menu" class="hero-btn">
        Check out our menu
      </nuxt-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<style scoped lang="scss">
.hero {
  position: absolute;
  top: 36%;
  color: white;

  h4 {
    font-style: italic;
    font-size: 16px;
  }

  h2 {
    font-weight: 800;
    font-size: 50px;
    line-height: 70px;
  }
}
</style>