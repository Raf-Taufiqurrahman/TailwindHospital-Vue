<template>
  <Navbar />
  <Hero />
  <Cta />
  <Service />
  <About />
  <Appointment />
  <Testimonial />
</template>

<script>
import Hero from './components/Hero.vue'
import Cta from './components/Cta.vue'
import Service from './components/Service.vue'
import About from './components/About.vue'
import Appointment from './components/Appointment.vue'
import Navbar from './components/Navbar.vue'
export default {
  components: {
    Hero,
    Cta,
    Service,
    About,
    Appointment,
    Navbar
  }
}
</script>
