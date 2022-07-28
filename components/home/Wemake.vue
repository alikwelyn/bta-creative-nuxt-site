<template>
    <div>
      <section id="wemake">
        <div class="container">
          <div class="row">
            <div class="col-md-12">
              <h1>we make</h1>
            </div>
          </div>
        </div>
      </section>
      <section id="digital">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <h1>digital</h1>
          </div>
        </div>
      </div>
    </section>
    <section id="relevant">
      <div class="container">
        <div class="row">
          <div class="col-md-12">
            <h1>relevant</h1>
          </div>
        </div>
      </div>
    </section>
    </div>
</template>

<script>
export default {
  name: 'Wemake'
}
</script>

<style>
#wemake{
  background-color: #fb1787;
  text-align: left;
}
#wemake h1{
  color: #202c49;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 250px;
}
#digital{
  background-color: #202c49;
  text-align: left;
}
#digital h1{
  color: #fb1787;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 250px;
}
#relevant{
  background-color: #fb1787;
  text-align: left;
}
#relevant h1{
  color: #202c49;
  font-family: 'Montserrat', sans-serif;
  font-weight: 300;
  font-size: 250px;
}
#relevant .circle {
  display: none;
}
</style>