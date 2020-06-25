<template>
  <button class="button" :class="colorClass">
    {{text}}
    <ArrowRight :fillColor="arrowColor" class="arrow-right"
                v-if="arrowIcon" />
  </button>
</template>

<script>
import ArrowRight from './SVGs/ArrowRight'

export default {
  name: 'Button',
  props: {
    text: { type: String, default: '' },
    arrowIcon: { type: Boolean, default: false },
    colorClass: { type: String, default: 'transparent' },
    arrowColor: { type: String, default: 'white' },
  },
  components: {
    ArrowRight
  }
};
</script>

<style scoped lang="scss">
.button {
  padding: 14px 20px;
  font-weight: 600;
  font-size: 13px;
  cursor: pointer;
  display: flex;
  align-items: center;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
}

.transparent {
  background: rgba(175, 175, 175, 0.3);
  color: #fff;
  border: 1px solid #C19D60;

  &:hover {
    background: white;
    color: black;

    .arrow-right {
      fill: black;
    }
  }
}

.black {
  background: rgb(31, 31, 31);
  color: #fff;
  border: unset;

  &:hover {
    background: #C19D60;
    color: white;
  }
}

.arrow-right {
  margin-left: 15px;
}
</style>