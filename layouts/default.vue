<template>
  <div>
    <NavContainer />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>
import NavContainer from '../components/Navbar/NavContainer'
import Footer from '../components/Footer'

export default {
  components: {
    NavContainer,
    Footer
  }
};
</script>

<style>

</style>
