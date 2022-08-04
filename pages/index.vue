<template>
  <div>
    <About />
    <Video />
    <Beseen />
    <Wemake />
    <Everywhere />
    <Partners />
    <WeHaveContent />
    <Contact />
  </div>
</template>

<script>
import About from '~/components/home/About.vue'
import Video from '~/components/home/Video.vue'
import Beseen from '~/components/home/Beseen.vue'
import Wemake from '~/components/home/Wemake.vue'
import Everywhere from '~/components/home/Everywhere.vue'
import Partners from '~/components/home/Partners.vue'
import WeHaveContent from '~/components/home/WeHaveContent.vue'
import Contact from '~/components/home/Contact.vue'

export default {
  name: 'IndexPage',
  components: {
      About,
      Video,
      Beseen,
      Wemake,
      Everywhere,
      Partners,
      WeHaveContent,
      Contact,
  }
}
</script>

<style>
.container {
  padding-right: 0;
  padding-left: 0;
}

/** BUTTONS **/
.btn-blue {
  color: #fff;
  background-color: #202c49;
  border-color: #202c49;
  padding: 5px 30px;
  font-size: 30px;
  font-family: 'Thasadith', sans-serif;
  font-weight: 700;

  -webkit-user-select: none;
  -moz-user-select: none;
  -ms-user-select: none;
  user-select: none;
  -webkit-transition: all .5s;
  -o-transition: all .5s;
  transition: all .5s;
}
.btn-blue:focus,
.btn-blue.focus {
  color: #202c49;
  background-color: transparent;
  border-color: 1px solid #202c49;
}
.btn-blue:hover {
  color: #202c49;
  background-color: transparent;
  border-color: 1px solid #202c49;
  -webkit-box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
  -webkit-transform: translateY(-2px);
  -ms-transform: translateY(-2px);
  transform: translateY(-2px);
}
.btn-blue:active,
.btn-blue.active {
  color: #202c49;
  background-color: transparent;
  border-color: 1px solid #202c49;
}
.btn-blue:active:hover,
.btn-blue.active:hover,
.btn-blue:active:focus,
.btn-blue.active:focus,
.btn-blue:active.focus,
.btn-blue.active.focus {
  color: #202c49;
  background-color: transparent;
  border-color: 1px solid #202c49;
}
</style>