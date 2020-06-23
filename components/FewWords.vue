<template>
  <section class="few-words">
    <div class="container">
      <div class="description-ctn">
        <h4>Our story</h4>
        <h2>A few words about us</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Error similique blanditiis eveniet suscipit, dicta mollitia delectus, quis obcaecati facere sequi vel aliquid perspiciatis debitis libero ipsa quisquam eum at quam?</p>
        <button>Explore our menu</button>
      </div>
      <img src="../assets/images/few-words.jpg" alt="">
    </div>
  </section>
</template>

<script>
export default {
  name: 'FewWords'
}
</script>

<style scoped>
.few-words > .container {
  display: flex;
}

img {
  height: 400px;
}
</style>