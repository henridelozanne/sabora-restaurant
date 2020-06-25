<template>
  <section class="quote-and-op-ctn">
    <Quote />
    <OpeningHours />
  </section>
</template>

<script>
import Quote from './Quote'
import OpeningHours from './OpeningHours'

export default {
  name: 'QuoteAndOpeningHours',
  components: {
    Quote, OpeningHours
  }
}
</script>

<style scoped lang="scss">
.quote-and-op-ctn {
  display: flex;
  height: 650px;

  & > * {
    width: 50%;
  }
}
</style>