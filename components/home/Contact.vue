<template>
    <div>
      <footer id="contato">
        <div class="container">
            <div class="row">
              <div class="col-md-12 ctt">
          <div class="row">
            <div class="col-sm-12">
              <h1>fale conosco</h1>
            </div>
          </div>
                <div role="form" class="wpcf7" id="wpcf7-f22-o1" lang="pt-BR" dir="ltr">
      <div class="screen-reader-response"><p role="status" aria-live="polite" aria-atomic="true"></p> <ul></ul></div>
      <form action="/bta/bta-site/#wpcf7-f22-o1" method="post" class="wpcf7-form init" novalidate="novalidate" data-status="init" clint-observable="btabta-site-1">
      <div style="display: none;">
      <input type="hidden" name="_wpcf7" value="22">
      <input type="hidden" name="_wpcf7_version" value="5.6.1">
      <input type="hidden" name="_wpcf7_locale" value="pt_BR">
      <input type="hidden" name="_wpcf7_unit_tag" value="wpcf7-f22-o1">
      <input type="hidden" name="_wpcf7_container_post" value="0">
      <input type="hidden" name="_wpcf7_posted_data_hash" value="">
      </div>
      <div class="row">
      <div class="col-sm-6 mx-auto">
      <div class="col-sm-12">
      <div class="form-group">
                <span class="wpcf7-form-control-wrap" data-name="nome"><input type="text" name="nome" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-validates-as-required form-control" aria-required="true" aria-invalid="false" placeholder="Nome"></span>
              </div>
      </div>
      <div class="col-sm-12">
      <div class="form-group">
                <span class="wpcf7-form-control-wrap" data-name="telefone"><input type="tel" name="telefone" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-tel wpcf7-validates-as-required wpcf7-validates-as-tel form-control" aria-required="true" aria-invalid="false" placeholder="Telefone de contato"></span>
              </div>
      </div>
      <div class="col-sm-12">
      <div class="form-group">
                <span class="wpcf7-form-control-wrap" data-name="email"><input type="email" name="email" value="" size="40" class="wpcf7-form-control wpcf7-text wpcf7-email wpcf7-validates-as-required wpcf7-validates-as-email form-control" aria-required="true" aria-invalid="false" placeholder="Email"></span>
              </div>
      </div>
      <div class="col-sm-12">
      <div class="form-group">
                <span class="wpcf7-form-control-wrap" data-name="mensagem"><textarea name="mensagem" cols="40" rows="10" class="wpcf7-form-control wpcf7-textarea wpcf7-validates-as-required form-control" aria-required="true" aria-invalid="false" placeholder="Mensagem"></textarea></span>
              </div>
      </div>
      <div class="col-sm-12">
      <div class="form-group">
      <p><span class="wpcf7-form-control-wrap" data-name="politica-de-privacidade"><span class="wpcf7-form-control wpcf7-checkbox"><span class="wpcf7-list-item first last"><input type="checkbox" name="politica-de-privacidade[]" value="Eu concordo em receber comunicações."><span class="wpcf7-list-item-label">Eu concordo em receber comunicações.</span></span></span></span><br>Ao informar meus dados, eu concordo com a <a href="http://localhost/bta/bta-site/politica-de-privacidade/">Política de Privacidade</a>.</p>
      </div>
      </div>
      <div class="col-sm-12">
                <input type="submit" value="enviar" class="wpcf7-form-control has-spinner wpcf7-submit btn btn-blue"><span class="wpcf7-spinner"></span>
          </div>
      </div>
      </div>
      <div class="wpcf7-response-output" aria-hidden="true"></div></form></div>        </div>
              <div class="col-md-12 pink">

                <div class="row">

                  <div class="col-md-1">
                  </div>

                  <div class="col-xs-12 col-md-4 align-self-center">
                    <a href="mailto:contato@btacreative.com.br" class="btn btn-blue" id="VerEmail" onclick="VerEmail();this.style.width = '370px';" rel="nofollow">ver email</a>
                  </div>

                  <div class="col-xs-12 col-md-3 align-self-center">
                    <a href="https://wa.me/551123125598" class="btn btn-blue" id="VerTelefone" onclick="VerTelefone();this.style.width = '300px';" target="_new" rel="nofollow">ver telefone</a>
                  </div>

                  <div class="col-xs-12 col-md-4 align-self-center">
                    <ul class="styled-icons icon-theme-colored list-inline">
                      <li><a href="https://www.facebook.com/btacreative" target="_blank"><i class="fa fa-facebook"></i></a></li>
                      <li><a href="https://www.instagram.com/btacreative" target="_blank"><i class="fa fa-instagram"></i></a></li>
                      <li><a href="https://www.youtube.com/channel/UCSa-mGcOQDTSZ9p0jUmE32A/" target="_blank"><i class="fa fa-youtube"></i></a></li>
                    </ul>
                  </div>

                </div>

              </div>
            </div>
          </div>
      </footer>
    </div>
</template>

<script>
export default {
  name: 'Contact',
}
</script>

<style>
footer{
  background: url("~/assets/footer.jpg") no-repeat;
}

footer .ctt{
  background-color: #fb1787;
  text-align: center;
  margin: 3em 0 0 0;
}

footer .ctt h1{
  color: #202c49;
  font-family: 'Montserrat', sans-serif;
  font-weight: 600;
  font-size: 40px;
  padding: 0.5em 0;
}

footer .ctt .btn-blue{
  padding: 1px 100px;
}

footer .ctt input.wpcf7-form-control.wpcf7-submit {
display: block;
margin: 0 auto;
}

footer .ctt input.wpcf7-form-control.wpcf7-submit:hover {
color: #fff;
}


footer .pink{
  background-color: #fb1787;
  text-align: center;
  margin: 2em 0;
}

footer .pink .btn-blue{
  padding: 5px 70px;
  font-size: 20px;
}

footer .pink .btn-blue:hover{
  color: #fff;
  background-color: transparent;
  border-color: 1px solid #fff;
}

.styled-icons a {
  color: #202c49;
  font-size: 40px;
  height: 40px;
  line-height: 40px;
  width: 40px;
  float: right;
  margin: 25px 7px 0px 0;
  text-align: center;
  -webkit-transition: all 0.3s ease-in-out;
  -o-transition: all 0.3s ease-in-out;
  transition: all 0.3s ease-in-out;
}
.styled-icons a:hover {
  color: #fff;
}
.styled-icons li {
  display: inline-block;
  padding-right: 2em;
}

.form-control {
  height: 45px;
  -webkit-border-radius: 0;
     -moz-border-radius: 0;
          border-radius: 0;
}

.form-control:focus,
form select:focus,
form textarea:focus {
  color: #404040;
  border-color: rgba(32, 44, 73, 0.3);
  -webkit-box-shadow: 0 0 3px rgba(32, 44, 73, 0.1);
  -moz-box-shadow: 0 0 3px rgba(32, 44, 73, 0.1);
  box-shadow: 0 0 3px rgba(32, 44, 73, 0.1);
  outline: none;
}

.form-group p{
  color: #fff;
}

.form-group a{
  color: #fff;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  text-decoration-line: underline;
  text-decoration-thickness: 2px;
}
</style>