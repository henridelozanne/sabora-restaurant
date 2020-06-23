<template>
  <div>
    <HeroTopSection />
    <FewWords />
    <Numbers />
    <MeetOurChefs />
    <Promo />
    <CustomerReviews />
  </div>
</template>

<script>
import HeroTopSection from '../components/HeroTopSection'
import FewWords from '../components/FewWords'
import Numbers from '../components/Numbers'
import MeetOurChefs from '../components/MeetOurChefs'
import Promo from '../components/Promo'
import CustomerReviews from '../components/CustomerReviews'

export default {
  name: 'about',
  components: {
    HeroTopSection,
    FewWords,
    Numbers,
    MeetOurChefs,
    Promo,
    CustomerReviews
  }
}
</script>

<style>

</style>