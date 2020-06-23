<template>
  <div class="navbar">
    <span>Sabora</span>
    <nav>
      <ul class="nav-list">
        <li>Home</li>
        <li>Menu</li>
        <li>About</li>
        <li>Contact</li>
      </ul>
    </nav>
    <button>RESERVATION</button>
  </div>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style lang="scss" scoped>
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;

  .nav-list {
    display: flex;
    list-style-type: none;
  }
}
</style>
