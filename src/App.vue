<template>
  <div id="app">
    <ContactUs />
    <!-- <AboutUs /> -->
  </div>
</template>

<script>
// Import the AboutUs component
import AboutUs from './components/AboutUs.vue';
import ContactUs from './components/ContactUs.vue'

export default {
  name: 'App',
  components: {
    AboutUs,
    ContactUs
  }
}
</script>

<style>
/* Add any global styles if necessary */
</style>
