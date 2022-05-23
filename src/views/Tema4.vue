<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 La comunicación con el cliente

    .row.mb-5
      .col-12.col-lg-4.mb-3
        figure
          img(src='@/assets/curso/tema4/t4-1.png', alt='Texto que describa la imagen')
      .col-12.col-lg-8
        p Hablar de comunicación con el cliente es referirse al contacto que se tiene con él y la información que se comparte, gracias a los diferentes mecanismos y a los avances tecnológicos se abren diversos canales de comunicación con el cliente, que los podemos usar con diferentes propósitos aprovechando sus características.
        p La importancia de la comunicación con el cliente consiste en que se mantenga viva la relación entre la empresa y los consumidores, ya que si no existe dicha comunicación el cliente se puede sentir desprotegido cuando necesite información sobre el producto o servicio que se le haya ofrecido por cualquiera de los canales que tenga para comunicarse; lo mismo puede suceder con clientes potenciales o clientes en condición de discapacidad, los cuales necesitan sentirse escuchados por la empresa.
        p Frecuentemente, se comete el error de utilizar los conceptos de información y comunicación de forma indistinta, cuando en realidad se dirigen a realidades diferentes.

    p.mb-5 Según el modelo de comunicación de Shannon and Weaver (Models y Communication, 2011) Las diferencias entre los dos conceptos son:
     
    .row.justify-center
      .col-12.col-md-10(data-aos="zoom-in-down")
        AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta tarjeta--azul")
          .row(titulo="Información.")
            .col-md-8.px-5
              p Es unidireccional, ya que va en una sola dirección y la persona que la recibe no puede responder ante ella y no puede emitir un mensaje de respuesta, se limita únicamente a recibirla.
            .col-md-4
              figure
                img(src='@/assets/curso/tema4/t4-2.svg', alt='Texto que describa la imagen')
          .row(titulo="Comunicación.")
            .col-md-8.px-5
              p Es bidireccional ya que una persona emite un mensaje y otra persona lo recibe, esto le permite reaccionar y dar respuesta inmediata sin importar lo que ocurra ante la situación que se presente, lo importante es que existe una retroalimentación al respecto.
            .col-md-4
              figure
                img(src='@/assets/curso/tema4/t4-3.svg', alt='Texto que describa la imagen')
    
    p La comunicación con el cliente debe ser clara para no confundir al público, no importa lo que le tenga que decir, lo importante es evitar confusiones que puedan dejarle una mala experiencia y reputación de la empresa.
    p.mb-5 ener una comunicación clara y adecuada don el cliente trae tres grandes beneficios.

    .row.mb-5
      .col-12.col-lg-4.mb-3.mb-lg-0
        div.p-4.bgr_9 
          figure.justify-center.mb-4
            img.img160(src='@/assets/curso/tema4/t4-4.svg', alt='Texto que describa la imagen')
          h4.text-center Disposición.
          p.mb-0.text-center Los clientes están dispuestos a pagar más por los productos o servicios si tienen una buena experiencia donde la comunicación sea eficiente.
      .col-12.col-lg-4.mb-3.mb-lg-0
        div.p-4.bgr_10 
          figure.justify-center.mb-4
            img.img160(src='@/assets/curso/tema4/t4-5.svg', alt='Texto que describa la imagen')
          h4.text-center Recompra.
          p.mb-0.text-center Cuando se logra tener una comunicación positiva se tiene más probabilidades de que el cliente vuelva a adquirir y recomendar los productos de la empresa, esto garantiza una relación duradera.
      .col-12.col-lg-4
        div.p-4.bgr_11 
          figure.justify-center.mb-4
            img.img160(src='@/assets/curso/tema4/t4-6.svg', alt='Texto que describa la imagen')
          h4.text-center Reputación.
          p.mb-0.text-center Una buena comunicación con los clientes genera una buena reputación de la empresa. Siempre hay que responder a sus dudas por todos los canales de comunicación, resolviendo las necesidades de los clientes.
    
    p De acuerdo al Manual de protocolo para la atención a personas en situación de discapacidad de la Cámara de Comercio de Medellín y a la Convención Internacional sobre los Derechos de las Personas con Discapacidad, así como al Servicio Nacional de la Discapacidad, existen pautas de comunicación para la atención al cliente en condición de discapacidad. Si consigue aplicarlas estará ampliando su mercado, lo que será rentable para su empresa y justo para esta población, ya que son personas que merecen las mismas oportunidades.
    p.mb-5 Se deben tener en cuenta las siguientes recomendaciones:

    .row.justify-center
      .col-12.col-lg-10
        .tabla-a.color-acento-contenido.mb-5 
          .tabla-b__header
            h5.mb-0 Recomendación
          table
            tbody
              tr
                td(data-aos="fade-right")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Dirigirse directamente a la persona discapacitada y no su acompañante.
                td(data-aos="fade-left")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Identificar las necesidades y dificultades de la persona con discapacidad.
              tr
                td(data-aos="fade-right")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Cuando el discapacitado es ciego se debe enseñar el nivel de accesibilidad del establecimiento haciendo una clara descripción de los ambientes por donde vaya a transitar, esto le dará precisión, claridad, confianza y seguridad.
                td(data-aos="fade-left")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Ofrecerle una información correcta es fundamental para su comprensión.
              tr
                td(data-aos="fade-right")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Evite sobreprotegerlo, no es una buena estrategia, ellos no lo necesitan y se sienten mal si el funcionario lo hace.
                td(data-aos="fade-left")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | No está bien preguntar por el tipo de discapacidad del cliente, ellos, por lo general, lo comentan cuando consideran que es necesario que usted lo sepa.
              tr
                td(data-aos="fade-right")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Sea cuidadoso con el contacto físico, evite tocarlos como también a sus ayudas técnicas (sillas de ruedas, bastones, etc.) sin que ellos lo soliciten, recuerde que estas herramientas son parte de su espacio personal.
                td(data-aos="fade-left")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Los discapacitados adultos hay que tratarlos de acuerdo con su edad, no se deben tomar decisiones sin consultarles.
              tr
                td(data-aos="fade-right")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Evite referirse a ellos como inválido, minusválido o discapacitado.
                td(data-aos="fade-left")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | Siempre debe preguntar si necesitan de su ayuda, ya que ellos la solicitan en el momento de necesitarla.
              tr
                td(data-aos="fade-right")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | El establecimiento debe estar bien ordenado, no debe haber obstáculos que dificulten la movilidad del cliente en condición de discapacidad.
                td(data-aos="fade-left")
                  ul.lista-ul
                    li.mt-2 
                      i.fas.fa-check-circle.colr_2
                      | No demuestre impaciencia, ofrézcale el tiempo necesario para que se sienta bien atendido.
      .col-12.col-lg-10
        div.bgr_6.d-flex
          p.my-3.px-3  <b>Nota.</b> Tomada de Cámara de Comercio de Medellín (s. f.).
             
    separador

    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade-right")
      h2 4.1 Características, tipos y elementos

    p La comunicación en general debe entenderse como un intercambio. El propósito no es que la conversación suceda desde un solo lado, la intención es provocar reacciones para que exista un flujo de ideas, la comunicación con los clientes sirve como canal para conocerlos mejor y que ellos a su vez conozcan su empresa. También, la comunicación comercial cumple con la función de promocionar una oferta.
    p.mb-5 Con el cliente, sin importar el canal debe recibir una comunicación con las siguientes características.

    .row.mb-5
      .col-12.col-lg-4.mb-3.mb-lg-0
        div.p-4.bgr_12 
          figure.justify-center.mb-4
            img.transf(src='@/assets/curso/tema4/t4-7.png', alt='Texto que describa la imagen')
          h4 Clara y sencilla
          p.mb-0 La comunicación con el cliente debe ser clara para no confundir al público, no importa lo que le tenga que decir, lo importante es evitar confusiones que puedan dejarle una mala experiencia y reputación de la empresa.
      .col-12.col-lg-4.mb-3.mb-lg-0
        div.p-4.bgr_12 
          figure.justify-center.mb-4
            img.transf(src='@/assets/curso/tema4/t4-8.png', alt='Texto que describa la imagen')
          h4 Activa
          p.mb-0 La comunicación con el cliente no debe convertirse en un monólogo, se debe estar preparado para las preguntas, ellas ayudan a comprender la necesidad o deseo de los productos o servicios que éste tiene de la empresa.
      .col-12.col-lg-4
        div.p-4.bgr_12 
          figure.justify-center.mb-4
            img.transf(src='@/assets/curso/tema4/t4-9.png', alt='Texto que describa la imagen')
          h4 Abierta
          p.mb-0 La transparencia genera confianza, sea claro con el cliente con respecto al uso y características del producto o servicio, dele a conocer con claridad las políticas de garantía del producto o servicio y no espere que le toque buscar la letra pequeña en los documentos de garantía o manual de funcionamiento.

    p.mb-5 En cuanto a los canales, en la actualidad existen muchos para comunicarse con los clientes, esto facilita la atención y servicio que se le debe prestar para que quede satisfecho con la empresa.
    
    .row.mb-5
      .col-12.col-lg-6
        ol.lista-ol--cuadro.mt-lg-4
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 1
            | Sitio web.
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 2
            | Línea telefónica.
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 3
            | SMS.
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 4
            span E-mail  #[strogn marketing]  y boletines electrónicos.
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 5
            | Redes sociales.
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 6
            span Notificaciones  <em>push</em>  (mensajes que se envían de un servidor remoto hasta los dispositivos).
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 7
            | Encuestas.
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 8
            | Anuncios.
          li 
            .lista-ol--cuadro__vineta.colr_3.text-bold
              span 9
            | Atención presencial.

      .col-12.col-lg-6
        figure
          img(src='@/assets/curso/tema4/t4-10.png', alt='Texto que describa la imagen')
    
    p.mb-5 Las empresas deben crear estrategias para tener una buena comunicación con sus clientes, sin importar el canal. Se deben evitar al máximo los errores ya que estos afectan la imagen de la empresa y hacen perder clientes. Ahora, se presentan los cuatro errores de comunicación más comunes en la interacción con los clientes.

    .tarjeta.p-lg-4(data-aos="zoom-out")
      SlyderA(tipo="b")
        .row.p-3.p-lg-5.bgr_13.h-100.mx-1
          .col-md-5
            div 
              img.img70.mb-3(src='@/assets/curso/tema4/t4-15.svg', alt='Texto que describa la imagen')
              h4.bgr_14 No investigar al cliente
              p Muchos ejecutivos de ventas cometen el error de contactar al cliente sin saber quién es antes de ir a una cita, enviar un correo electrónico o hacer una llamada. Asegúrese de saber con quién se va a comunicar, debe conocer en qué empresa trabaja, el cargo que desempeña y la profesión del cliente.
          .col-md-7.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema4/t4-11.png', alt='Texto que describa la imagen')
        .row.p-3.p-lg-5.bgr_13.h-100.mx-1
          .col-md-5
            div 
              img.img70.mb-3(src='@/assets/curso/tema4/t4-15.svg', alt='Texto que describa la imagen')
              h4.bgr_14 No escuchar al cliente
              p Debe poner mucha atención a lo que el cliente le diga, en las conversaciones telefónicas se comete este error ya que como no lo están viendo puede distraerse, lo que conlleva a la interrupción o la repetición de lo que el cliente le esté diciendo, antes de hacer una llamada se deben planificar los temas a tratar y disponer del tiempo necesario para no pausar la llamada.
          .col-md-7.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema4/t4-12.png', alt='Texto que describa la imagen')
        .row.p-3.p-lg-5.bgr_13.h-100.mx-1
          .col-md-5
            div 
              img.img70.mb-3(src='@/assets/curso/tema4/t4-15.svg', alt='Texto que describa la imagen')
              h4.bgr_14 No hablar con naturalidad
              p Con sorprendente frecuencia las personas imitan las actitudes corporales de los demás, ya que dos personas que comparten un mismo punto de vista suelen tener también una misma postura.
          .col-md-7.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema4/t4-13.png', alt='Texto que describa la imagen')
        .row.p-3.p-lg-5.bgr_13.h-100.mx-1
          .col-md-5
            div 
              img.img70.mb-3(src='@/assets/curso/tema4/t4-15.svg', alt='Texto que describa la imagen')
              h4.bgr_14 No contar con suficientes conocimientos o recursos
              p Los clientes se frustran cuando la persona que los atiende no cuenta con los recursos suficientes o información para colaborarle con sus problemas o inquietudes, en estos casos el asesor debe saber dirigirlo al software de quejas y reclamos (CRM) para que le resuelvan sus dudas, pero antes de esto debe procurar resolver por sí mismo la situación.
          .col-md-7.mb-4.mb-md-0
            figure
              img(src='@/assets/curso/tema4/t4-14.png', alt='Texto que describa la imagen')
     

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>

<style lang="sass"></style>
