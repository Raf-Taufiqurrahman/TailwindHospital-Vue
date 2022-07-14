<template>
  <Hero />
  <Cta />
  <Service />
  <About />
  <Appointment />
</template>

<script>
import Hero from './components/Hero.vue'
import Cta from './components/Cta.vue'
import Service from './components/Service.vue'
import About from './components/About.vue'
import Appointment from './components/Appointment.vue'
export default {
  components: {
    Hero, Cta, Service, About, Appointment
  }
}
</script>
