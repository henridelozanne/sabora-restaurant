<template>
  <div class="landing">
    <img src="../../assets/images/landing.jpg" alt="">
    <SocialButtons />
    <Hero />
    <ImportantButton />
  </div>
</template>

<script>
import Hero from './Hero'
import ImportantButton from './ImportantButton'
import SocialButtons from './SocialButtons'

export default {
  name: 'Landing',
  components: {
    ImportantButton,
    Hero,
    SocialButtons
  }
}
</script>

<style lang="scss">
.landing {
  display: flex;
  justify-content: space-between;
  position: relative;
  height: 100vh;

  img {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100vh;
    z-index: -1;
    object-fit:  cover;
    object-position: top;
    filter: brightness(60%);
  }
}
</style>