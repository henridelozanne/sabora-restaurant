<template>
  <section class="few-words">
    <div class="container">
      <div class="description-ctn">
        <h4 class="section-over-header">Our story</h4>
        <h2>A few words about us</h2>
        <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Error similique blanditiis eveniet suscipit, dicta mollitia delectus, quis obcaecati facere sequi vel aliquid perspiciatis debitis libero ipsa quisquam eum at quam?</p>
        <Button :text="'Explore our menu'" :arrow-icon="true"
                :colorClass="'black'" :arrowColor="'white'" />
      </div>
      <img src="../assets/images/few-words.jpg" alt="">
    </div>
  </section>
</template>

<script>
import Button from './Button'

export default {
  name: 'FewWords',
  components: {
    Button
  }
}
</script>

<style scoped lang="scss">
.few-words {
  padding: 140px 0;

  .container {
    display: flex;

    .description-ctn {
      margin: auto 0;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: flex-start;

      p {
        width: 80%;
        color: rgb(113, 113, 113);
      }

      .button {
        margin-top: 30px;
      }
    }
  } 
}

img {
  height: 400px;
}
</style>