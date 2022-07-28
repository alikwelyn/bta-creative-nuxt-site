<template>
    <div>
		<section id="quemsomos">
			<div class="container">
				<div class="row">

					<div class="col-md-6 pd">
						<div class="titulo">
							<h1>better<br>times<br>ahead</h1>
						</div>  
						<p class="texto">
							Ou em bom português:<br>
							tempos melhores logo a frente.<br><br>

							Mais do que um nome bonitinho,<br>
							uma verdade que a gente<br>
							leva muito a sério.<br><br>

							Um ode responsável ao otimismo.<br>
							O que, do ponto de vista de marketing<br>
							digital, significa performance, criatividade,<br>
							resultado real e uma dose de paixão e<br>
							entrega extra que faz toda<br>
							a diferença.<br><br>

							Ou seja, não importa o quão lucrativo<br>
							e saudável esteja a sua empresa no<br>
							momento, faremos de tudo para que<br>
							tempos melhores ainda<br>
							sempre cheguem.
						</p>
						<div class="bonequinho wow fadeIn"></div>
					</div>

					<div class="col-md-6">
					</div>

				</div>
			</div>
		</section>
    </div>
</template>

<script>
export default {
  name: 'About'
}
</script>

<style>
#quemsomos {
  background: url("~/assets/sorridente.jpg") no-repeat;
}
#quemsomos .pd {
  text-align: left;
  margin: 5em 0 4em 0;
}
#quemsomos div.titulo h1 {
  color: #fb1787;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 65px;
  text-decoration-line: underline;
  text-decoration-thickness: 4px;
}
#quemsomos .bonequinho {
  background: url("~/assets/bonequinho.svg") no-repeat center transparent;
  width: 100%;
  height: 157px;
  position: absolute;
  right: 20.5%;
  top: 24.5%;
}
#quemsomos p.texto {
  color: #6d6e71;
  font-size: 15px;
  padding: 2.3em 0 0 0;
  line-height: 1.2;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  text-align: left;
}
#quemsomos p.texto:before {
  content: '';
  background-image: url("~/assets/arrow.svg");
  position: absolute;
  display: inline;
  left: 22.5%;
  width: 40px;
  height: 40px;
  bottom: 9.5%;
  animation: slide 2.2s ease-in-out infinite;
}
@keyframes slide {
  0%,
  100% {
    transform: translate(0, 0);
  }

  50% {
    transform: translate(0, 10px);
  }
}
</style>