<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción
    
    p.mb-5 Le damos la bienvenida al componente formativo <b>“Protocolos de servicio al cliente”</b>, y para comenzar satisfactoriamente este recorrido se invita a explorar el recurso que se muestra a continuación:
    
    .bg_grad-01(data-aos="fade-down")
      .row.justify-center.pt-5.pb-5
        .col-12.col-md-10
          figure
            .video
              iframe(width="560" height="315" src="https://www.youtube.com/embed/VdBU-D7dDXg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
  
</template>

<script>
export default {
  name: 'Introduccion',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass"></style>
