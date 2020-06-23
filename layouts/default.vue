<template>
  <div>
    <!-- <NavContainer /> -->
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
}

.container {
  max-width: 1224px;
  width: 92%;
  margin: 0 auto;
}

.hero-btn {
  border: 1px solid #C19D60;
  padding: 14px 20px;
  background: rgba(255,255,255,0.1);
  color: #fff;
  font-weight: 600;
  font-size: 13px;
  text-decoration: none;
}
</style>
