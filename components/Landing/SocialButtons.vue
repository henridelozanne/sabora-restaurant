<template>
  <ul class="social-buttons">
    <li>
      <nuxt-link to="#">
        <Facebook class="social-link" />
      </nuxt-link>
    </li>
    <li>
      <nuxt-link to="#">
        <Instagram class="social-link" />
      </nuxt-link>
    </li>
    <li>
      <nuxt-link to="#">
        <Twitter class="social-link" />
      </nuxt-link>
    </li>
    <li>
      <nuxt-link to="#">
        <LinkedIn class="social-link" />
      </nuxt-link>
    </li>
  </ul>
</template>

<script>
import Facebook from '../SVGs/Facebook'
import Instagram from '../SVGs/Instagram'
import Twitter from '../SVGs/Twitter'
import LinkedIn from '../SVGs/LinkedIn'

export default {
  name: 'SocialButtons',
  components: {
    Facebook, Instagram, Twitter, LinkedIn
  }
}
</script>

<style lang="scss">
.social-link {
  fill: white;
  width: 17px;
  height: 17px;
  padding: 13px;
  background: rgba(155, 155, 155, 0.3);
  border: 1px solid rgb(199, 199, 199);
  margin-block-start: 0;
  margin-block-end: 0;
  margin-inline-start: 0;
  margin-inline-end: 0;
  padding-inline-start: 0;

  &:hover {
    background: white;
    fill: #C19D60;
    border-color: #C19D60;
  }
}
</style>

<style scoped>
.social-buttons {
  list-style-type: none;
  padding-left: 0;
  position: absolute;
  left: 50px;
  top: 42%;
  display: flex;
  flex-direction: column;
}
</style>