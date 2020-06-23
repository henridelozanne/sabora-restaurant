<template>
  <div>
    <Map />
    <div style="display: flex;">
      <ContactForm />
      <OpeningHours />
    </div>
  </div>
</template>

<script>
import Map from '../components/Map'
import ContactForm from '../components/ContactForm'
import OpeningHours from '../components/OpeningHours'

export default {
  name: 'Contact',
  components: {
    Map,
    ContactForm,
    OpeningHours
  }
}
</script>

<style>

</style>