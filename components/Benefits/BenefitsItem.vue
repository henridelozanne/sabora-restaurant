<template>
  <div class="benefit-item">
    <div class="bg-img" :class="item.class"></div>
    <div class="text-info">
      <h2>{{item.title}}</h2>
      <h4>{{item.subTitle}}</h4>
    </div>
    <div class="index">{{index + 1}}.</div>
  </div>
</template>

<script>
export default {
  name: 'BenefitsItem',
  props: {
    item: { type: Object, default: () => {} },
    index: { type: Number, default: 0 },
  }
}
</script>

<style lang="scss" scoped>
.benefit-item {
  height: 400px;
  width: 33.33%;
  background-size: cover;
  position: relative;
  padding: 0 15px;

  .bg-img {
    background-size: cover;
    filter: brightness(50%);
    height: 100%;
  }

  .text-info {
    text-align: center;
    color: white;
    font-family: Prada, serif;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
  }

  .index {
    position: absolute;
    color: white;
    font-family: Prada, serif;
    bottom: 30px;
    left: 30px;
    font-size: 18px;
  }
}

.benefit-1 {
  background-image: url('../../assets/images/benefit-1.jpg');
}

.benefit-2 {
  background-image: url('../../assets/images/benefit-2.jpg');
}

.benefit-3 {
  background-image: url('../../assets/images/benefit-3.jpg');
}
</style>