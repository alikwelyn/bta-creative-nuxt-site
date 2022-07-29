<template>
    <div>
      <section id="beseen">
        <div class="container">
          <div class="row">

              <div class="col-md-6 col-sm-push-8 pd2">
              </div>

              <div class="col-md-6 order-sm-12 pd">
                <div class="titulo">
                  <h1>be seen.<br>be heard.<br>be known.</h1>
                </div>  

                <p class="texto">
                Se você não é um filhote fofinho de gato, temos<br>
                uma boa e uma má notícia pra você.<br>
                A má é que pouca gente vai te dar atenção de fato<br>
                na internet.<br>
                A boa é que dá para mudar isso. E aqui na BTA,<br>
                somos um time de profissionais especialistas em<br>
                fazer isso acontecer.<br><br>

                Somos especialistas em <strong>campanhas criativas,<br>
                Google ads, Facebook ads, Waze ads, Linkedin<br>
                ads, geração de leads, Inbound marketing,<br>
                geração de conteúdo, estratégia e planejamento<br>
                digital e OFFLINE</strong>. Mas, principalmente,<br>
                especialistas em eficiência.<br><br>

                Pra gente, criatividade e performance andam de<br>
                mãos dadas, e uma não vive sem a outra. Não basta<br>
                ser só legal, tem que ser eficaz e tem que performar<br>
                bem no ambiente digital. Senão não funciona. E<br>
                tudo tem que ser construído em cima de dados.
                </p>
                <div class="nuvem"></div>
              </div>

          </div>
        </div>
      </section>
    </div>
</template>

<script>
export default {
  name: 'Beseen'
}
</script>

<style>
#beseen{
  background: url("assets/gatinho.jpg") no-repeat;
}
#beseen > div.container{
  padding-top: 0;
  padding-bottom: 0;
}
#beseen .pd{
  text-align: left;
  padding-left: 11em;
  margin: 5em 0 4em 0;
}
#beseen div.titulo h1{
  color: #fb1787;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 65px;
  text-decoration-line: underline;
  text-decoration-thickness: 4px;
}

#beseen .nuvem {
  background: url("assets/nuvem.svg") no-repeat center transparent;
  width: 100%;
  height: 157px;
  position: absolute;
  bottom: -10%;
  right: 45%;
}

#beseen p.texto{
  color: #6d6e71;
  font-size: 15px;
  padding: 2.3em 0 0 0.1em;
  line-height: 1.2;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  text-align:left;
}
#beseen p.texto:after {
  content: '';
  background-image: url("~/assets/arrow.svg");
  position: absolute;
  right: 33%;
  bottom: -6%;
  width: 40px;
  height: 40px;
  animation: slide 2.2s ease-in-out infinite;
}
#beseen p.texto strong {
  color: #6d6e71;
}
</style>