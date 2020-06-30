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
body {
  margin: 0;
  font-family: 'Montserrat', sans-serif;
}

.container {
  max-width: 1224px;
  width: 92%;
  margin: 0 auto;
}

.section-over-header {
  margin: 0;
  font-style: italic;
  color: #C19D60;
  font-weight: 500;
  font-family: Prada, serif;
}
</style>
