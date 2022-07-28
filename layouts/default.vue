<template>
  <div>
    <Navbar />
    <Nuxt />
    <Footer />
  </div>
</template>

<script>

import Navbar from '~/components/inc/Navbar.vue'
import Footer from '~/components/inc/Footer.vue'

export default {
    name: 'default',
    components: {
        Navbar,
        Footer
    }
}
</script>

<style>

</style>