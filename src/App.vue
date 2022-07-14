<template>
  <Hero />
  <Cta />
  <Service />
</template>

<script>
import Hero from './components/Hero.vue'
import Cta from './components/Cta.vue'
import Service from './components/Service.vue'
export default {
  components: {
    Hero, Cta, Service
  }
}
</script>
