<template>
  <div>
    <h1>Nav container</h1>
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

<style>

</style>