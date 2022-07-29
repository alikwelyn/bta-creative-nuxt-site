<template>
  <div>
    <About />
    <Video />
    <Beseen />
    <Wemake />
    <Everywhere />
    <Partners />
  </div>
</template>

<script>
import About from '~/components/home/About.vue'
import Video from '~/components/home/Video.vue'
import Beseen from '~/components/home/Beseen.vue'
import Wemake from '~/components/home/Wemake.vue'
import Everywhere from '~/components/home/Everywhere.vue'
import Partners from '~/components/home/Partners.vue'

export default {
  name: 'IndexPage',
  components: {
      About,
      Video,
      Beseen,
      Wemake,
      Everywhere,
      Partners,
  }
}
</script>

<style>
.container {
  padding-right: 0;
  padding-left: 0;
}
</style>