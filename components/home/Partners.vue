<template>
    <div>
      <section id="partners">
        <div class="container">
          <div class="row align-items-center aos-init aos-animate" data-aos="fade-right" data-aos-duration="500" data-aos-once="true">
            <div class="col-md-5">
              <h1>clients</h1>
              <h2>partners</h2>
            </div>
            <div class="col-md-7">

            <div class="row clients bord">

				<hooper :settings="hooperSettings">
					<slide>
						<a href="#" target="new">
							<img src="~/assets/clientes/vira-jeri.svg" width="200">
						</a>
					</slide>
					<slide>
						<a href="#" target="new">
							<img src="~/assets/clientes/keep-young.svg" width="200">
						</a>
					</slide>
					<slide>
						<a href="#" target="new">
							<img src="~/assets/clientes/atelia867.svg" width="200">
						</a>
					</slide>
					<slide>
						<a href="#" target="new">
							<img src="~/assets/clientes/batucada-dez.svg" width="200">
						</a>
					</slide>
					<hooper-navigation slot="hooper-addons"></hooper-navigation>

				</hooper>
            </div>

            </div>
          </div>
        </div>
      </section>
    </div>
</template>

<script>
import {
  Hooper,
  Slide,
  Navigation as HooperNavigation
} from 'hooper';
import 'hooper/dist/hooper.css';

export default {
  name: 'Partners',
  components: { 
    Hooper,
    Slide,
    HooperNavigation
  },
  data: () => ({
    hooperSettings: {
		autoPlay: 1,
		playSpeed: 1500,
		itemsToShow: 3,
		infiniteScroll: 1,
		rtl: 1,
		wheelControl: 0,
		hoverPause: 1,
		trimWhiteSpace: 1,
		centerMode: 1,
    },
  }),
}
</script>

<style>
#partners{
  background-color: #fff;
  text-align: left;
  padding: 8em 0;
}
#partners h1{
  color: #fb1787;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 67.35px;
  padding-left: 0.5em;
  text-decoration-line: line-through;
  text-decoration-thickness: 8px;
  text-decoration-color: #202c49;
  text-overline-width: 100px;
}
#partners h2{
  color: #fb1787;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 67.35px;
  padding-left: 0.5em;
}
#partners .hooper-list {
    padding-top: 25px;
}
#partners .hooper-track {
    align-items: baseline;
}
#partners .hooper-navigation.is-rtl .hooper-prev {
    left: auto;
    right: -40px;
}
#partners .hooper-navigation.is-rtl .hooper-next {
    right: auto;
    left: -68px;
}
svg.icon.icon-arrowRight {
    fill: #fb1787;
}
svg.icon.icon-arrowLeft {
    fill: #fb1787;
}
</style>