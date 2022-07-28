<template>
  <div>
    <div class="footer-bottom">
      <div class="container">
        <div class="row">
          <div class="col-xs-12 col-md-4 bta order-first order-md-first order-lg-first">
            <img src="https://btacreative.com.br/wp-content/themes/bta/images/logo-bta-principal.svg" width="75" alt="BTA Creative">
          </div>
          <div class="col-xs-12 col-md-4 end order-last order-md-second order-lg-second">
            <p>Av. Ver. Narciso Yague Guimarães, 1145<br>Helbor Concept Office  |  Sala 1013<br>Jd. Armênia  |  Mogi das Cruzes  |  SP</p>
          </div>
          <div class="col-xs-12 col-md-4 certs order-second order-md-last order-lg-last">
            <a href="https://www.google.com/partners/agency?id=6247604136" target="_new"><img src="https://btacreative.com.br/wp-content/themes/bta/images/google-partner.svg" width="100" alt="Google Partner"></a>
                  <a href="https://marketplace.rdstation.com/parceiro/bta-creative/" target="_new"><img src="https://btacreative.com.br/wp-content/themes/bta/images/rd-station.svg" width="100" alt="RD Station Partners 2020"></a>
            <a href="https://btacreative.com.br/wp-content/uploads/2022/05/CERTIFICADO-2021-2022.pdf" target="_new"><img src="https://btacreative.com.br/wp-content/themes/bta/images/cenp.png" width="100" alt="CENP: Conselho Executivo das Normas-Padrão"></a>
            <!--<script src="https://apis.google.com/js/platform.js" async defer></script>
            <div class="g-partnersbadge" data-agency-id="2336299393"></div>-->
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Footer'
}
</script>

<style>
.footer-bottom {
  background-color: #202c49;
}

.footer-bottom .row {
  padding: 2em 0 2em 0;
}

.footer-bottom .bta {
  text-align: left;
}

.footer-bottom .bta img {
  margin-top: 1em;
}

.footer-bottom .end, span {
  color: #fff;
  text-align: center;
  font-family: 'Montserrat', sans-serif;
  font-weight: 400;
  font-size: 14px;
}

.footer-bottom .certs {
  text-align: right;
}

.footer-bottom .certs img {
  margin-top: 1em;
}
</style>