<template>
  <div class="container benefits">
    <h4 class="section-over-header">Why people choose us</h4>
    <h2>Prepare for first-class service</h2>
    <div class="cards-ctn">
      <BenefitsItem v-for="(item, index) in items" :key="item"
                    :item="item" :index="index" />
    </div>
  </div>
</template>

<script>
import BenefitsItem from './BenefitsItem'

export default {
  name: 'Benefits',
  components: {
    BenefitsItem
  },
  data() {
    return {
      items: [
        {
          title: 'Daily new fresh menus',
          subTitle: 'Start eating better',
          class: 'benefit-1'
        },
        {
          title: 'Fresh ingredients, tasty meals',
          subTitle: 'Quality is the most important',
          class: 'benefit-2'
        },
        {
          title: 'Creative & talented chefs',
          subTitle: 'Hot and ready to serve',
          class: 'benefit-3'
        }
      ]
    };
  },
}
</script>

<style scoped lang="scss">
.benefits {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 140px 0;
  
  .cards-ctn {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    margin-top: 40px;
  }
}
</style>