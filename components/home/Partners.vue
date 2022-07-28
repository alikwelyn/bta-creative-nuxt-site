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
            </div>

            </div>
          </div>
        </div>
      </section>
    </div>
</template>

<script>
export default {
  name: 'Partners'
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


.clients .brands:hover img {
	-webkit-transform: scale(50%);
	-ms-transform: scale(50%);
	transform: scale(50%);
	opacity: 1; }
  
  .clients .brands:hover .link {
	opacity: 1 !important;
	-webkit-transition: all 0;
	-o-transition: all 0;
	transition: all 0; }
  
  .clients .brands .item {
	text-align: center;
}
  
  .clients .brands .img {
	position: relative; }
	.clients .brands .img img {
	  -webkit-transition: all .4s;
	  -o-transition: all .4s;
	  transition: all .4s; }
	.clients .brands .img .link {
	  font-size: 13px;
	  width: -webkit-max-content;
	  width: -moz-max-content;
	  width: max-content;
	  position: absolute;
	  top: 50%;
	  left: 50%;
	  -webkit-transform: translateX(-50%);
	  -ms-transform: translateX(-50%);
	  transform: translateX(-50%);
	  opacity: 0;
	  -webkit-transition: all .3s;
	  -o-transition: all .3s;
	  transition: all .3s; }
  
  .clients .bord .item {
	margin-bottom: 30px; }
  
  .clients-brand .brands:hover .img {
	-webkit-transform: scale(0);
	-ms-transform: scale(0);
	transform: scale(0);
	opacity: 0; }
  
  .clients-brand .item {
	position: relative;
	text-align: center; }
	.clients-brand .item .link {
	  font-size: 16px;
	  width: -webkit-max-content;
	  width: -moz-max-content;
	  width: max-content;
	  position: absolute;
	  top: 0;
	  left: 50%;
	  -webkit-transform: translateX(-50%);
	  -ms-transform: translateX(-50%);
	  transform: translateX(-50%);
	  opacity: 0;
	  -webkit-transition: all .3s;
	  -o-transition: all .3s;
	  transition: all .3s; }
  
  .clients-brand .img {
	max-width: 85px;
	margin: auto;
	position: relative;
	-webkit-transition: all .4s;
	-o-transition: all .4s;
	transition: all .4s; }

	.clients-brand .item a {
		width: 80px;
		opacity: .5; }
		.clients-brand .item a:hover {
		  opacity: 1; }

.owl-controls {
  margin: 0;
}
.owl-controls .owl-nav > div {
  background: none repeat scroll 0 0 rgba(240, 240, 240, 0.0);
  border-radius: 0;
  display: block;
  margin: 0;
  padding: 10px;
  position: absolute;
  top: 30%;
  -webkit-transition: all 0.4s ease 0s;
  -o-transition: all 0.4s ease 0s;
  transition: all 0.4s ease 0s;
  z-index: 6;
}
.owl-controls .owl-next {
  right: -3em;
}
.owl-controls .owl-next i {
  color: #fb1787;
  font-size: 40px;
}
.owl-controls .owl-prev {
  left: -3em;
}
.owl-controls .owl-prev i {
  color: #fb1787;
  font-size: 40px;
}
</style>