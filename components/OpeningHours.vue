<template>
  <div class="opening-hours">
    <h4>Call for reservation</h4>
    <h2>Opening Hours</h2>
    <div class="hours">
      <div>
        <span>Sunday to Tuesday</span>
        <div>09:00</div>
        <div>22:00</div>
      </div>
      <div>
        <span>Friday to Saturday</span>
        <div>11:00</div>
        <div>19:00</div>
      </div>
    </div>
    <Button class="phone-number" text="+227363584" />
  </div>
</template>

<script>
import Button from './Button'

export default {
  name: 'OpeningHours',
  components: {
    Button
  }
}
</script>

<style lang="scss">
.opening-hours {
  background: rgb(40, 40, 40);
  color: white;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

  h4 {
    font-style: italic;
    color: #C19D60;
    font-weight: 300;
    font-family: Prada, serif;
    margin: 0;
  }

  h2 {
    margin: 40px 0;
  }

  .hours {
    display: flex;
    text-align: center;

    >div:first-of-type {
      margin-right: 60px;
    }

    div span {
      color: #C19D60;
      font-size: 14px;
    }

    div {
      div {
        font-size: 30px;
        font-weight: 800;
      }

      div:first-of-type {
        margin-top: 10px;
      }
    }
  }

  .phone-number {
    margin-top: 40px;
  }
}
</style>