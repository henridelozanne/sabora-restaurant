<template>
  <div class="container">
    <Landing />
    <FewWords />
    <QuoteAndOpeningHours />
    <Benefits />
    <MenuSmall />
    <MeetOurChefs />
    <CustomerReviews />
  </div>
</template>

<script>
import Landing from '../components/Landing'
import FewWords from '../components/FewWords'
import QuoteAndOpeningHours from '../components/QuoteAndOpeningHours'
import Benefits from '../components/Benefits'
import MenuSmall from '../components/MenuSmall'
import MeetOurChefs from '../components/MeetOurChefs'
import CustomerReviews from '../components/CustomerReviews'

export default {
  name: 'index',
  components: {
    Landing,
    FewWords,
    QuoteAndOpeningHours,
    Benefits,
    MenuSmall,
    MeetOurChefs,
    CustomerReviews,
  }
}
</script>

<style>

</style>
