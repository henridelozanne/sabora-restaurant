<template>
  <div class="container">
    <div class="hero">
      <h4>Quality food in a beautiful place</h4>
      <h2>Welcome to Sabora Restaurant</h2>
      <Button :text="'Check out our menu'" :colorClass="'transparent'"
              :arrowIcon="true" :arrowColor="'white'" />
    </div>
  </div>
</template>

<script>
import Button from '../Button'

export default {
  name: 'Hero',
  components: {
    Button
  }
}
</script>

<style scoped lang="scss">
.hero {
  position: absolute;
  top: 36%;
  color: white;
  max-width: 800px;

  h4 {
    font-style: italic;
    font-size: 16px;
    font-weight: 500;
    font-family: Prata, serif;
  }

  h2 {
    font-weight: 800;
    font-size: 50px;
    line-height: 70px;
  }
}
</style>