<template>
  <div class="quote">
    <div class="bg-img" />
    <div class="quote-inner-ctn">
      <QuoteLogo class="quote-logo" />
      <p>Lorem ipsum dolor sit amet consectetur elit.  eligendi ad, amet perferendis quas blanditiis laboriosam temporibus ipsum dolor sit amet consectetur elit. ipsum dolor sit amet consectetur elit. ipsum dolor sit amet consectetur elit. unde reiciendis quod eveniet voluptatum eaque in! Optio, harum deleniti!</p>
      <h4>Jorge Spalito</h4>
    </div>
  </div>
</template>

<script>
import QuoteLogo from './SVGs/QuoteLogo'

export default {
  name: 'Quote',
  components: {
    QuoteLogo
  }
}
</script>

<style lang="scss" scoped>
.quote {
  position: relative;
  
  .bg-img {
    background-image: url('../assets/images/quote.jpg');
    background-size: cover;
    filter: brightness(50%);
    height: 100%;
  }

  .quote-inner-ctn {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    color: white;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    font-family: Prata, serif;
    z-index: 2;

    .quote-logo {
      height: 120px;
      width: 120px;
      fill: #C19D60;
      margin-bottom: 40px;
    }

    p {
      width: 85%;
      line-height: 34px;
    }
  }
}
</style>