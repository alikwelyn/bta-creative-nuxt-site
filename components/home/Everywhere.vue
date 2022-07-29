<template>
    <div>
      <section id="everywhere">
        <div class="container">
          <div class="row">

              <div class="col-md-6 pd">
                <div class="titulo">
                  <h1>we are<br>everywhere.</h1>
                </div>  
                <p class="texto">
                Somos especialistas em eficiência e, independentemente de onde você esteja, vamos ajudar a  sua empresa a fazer bonito no marketing digital. Atuamos a distância e em todos os lugares.<br><br>

                Temos parceiros em São Paulo, Minas Gerais, Mato Grosso do Sul, Santa Catarina, Ceará e até fora do Brasil, lá nos Estados Unidos! Para nós, distância não é problema quando o assunto é ajudar o seu negócio com criatividade e estratégia.<br><br>

                Se a sua empresa busca uma agência especializada em campanhas criativas, Google Ads, campanhas pagas nas redes sociais, geração de leads, Inbound Marketing, geração de conteúdo, estratégia e planejamento digital e offline, a BTA Creative é a parceira certa para você.
                </p>
                <div class="bonequinho"></div>
              </div>

              <div class="col-md-6 pd2">
              </div>

          </div>
        </div>
      </section>
    </div>
</template>

<script>
export default {
  name: 'Everywhere'
}
</script>

<style>
#everywhere{
  background: url("assets/personagem-mundo.jpg") no-repeat;
}
#everywhere > div.container{
  padding-top: 0;
  padding-bottom: 0;
}
#everywhere .pd{
  text-align: left;
  padding-left: 2.7em;
  margin: 6em 0 4.7em 0;
}
#everywhere div.titulo h1{
  color: #fb1787;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 65px;
  text-decoration-line: underline;
  text-decoration-thickness: 4px;
}
#everywhere p.texto{
  color: #6d6e71;
  font-size: 15px;
  padding: 2.3em 0 0 0.1em;
  line-height: 1.2;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  width: 70%;
  text-align:left;
}
#everywhere p.texto:before {
  content: '';
  background-image: url("assets/arrow.svg");
  position: absolute;
  display: inline;
  left: 33%;
  width: 40px;
  height: 40px;
  bottom: -4.5em;
  animation: slide 2.2s ease-in-out infinite;
}
</style>