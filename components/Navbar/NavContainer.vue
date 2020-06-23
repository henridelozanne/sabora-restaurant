<template>
  <div class="nav-container container">
    <TopNavbar />
    <Navbar />
  </div>
</template>

<script>
import Navbar from './Navbar'
import TopNavbar from './TopNavbar'

export default {
  name: 'NavContainer',
  components: {
    Navbar,
    TopNavbar
  }
}
</script>

<style scoped>
.nav-container {
  /* position: fixed;
  top: 0;
  left: 0;
  right: 0;
  z-index: 100; */
}
</style>