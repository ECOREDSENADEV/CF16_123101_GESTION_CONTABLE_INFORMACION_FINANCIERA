<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 Costos
    div(style="background-color: #DDEFFD ")
      .row.justify-content-center.align-items-center
        .col-lg-5.col-7: img(src='@/assets/curso/temas/4.png', alt='')
        .col-lg-7
          .p-4
            p.mb-0 Es de recordar que los costos hacen énfasis al dinero que una empresa invierte para la producción de algún tipo de bien o servicio, es decir, son los recursos económicos que se utilizan para la producción, donde se incluyen los valores del producto y/o prestación del servicio, con el fin de determinar el precio de venta para ofrecer en el mercado.
    Separador
    #t_1_1.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 1.1  Concepto de contabilidad de costos
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8.mb-lg-0.mb-3
        p.mb-0 En el ámbito empresarial este concepto es aplicable a los diferentes tipos de contabilidad, como pueden ser financiera, administrativa o de costos; en esta unidad se hace énfasis en la contabilidad de costos, teniendo en cuenta su importancia en las diferentes empresas.
          br
          br
          |La contabilidad de costos hace referencia al proceso de recopilar información que permita calcular el valor de la producción de un bien o prestación de servicios para planear, controlar y tomar decisiones que permitan generar rentabilidad a la empresa.
      .col-lg-4.col-7: img(src='@/assets/curso/temas/5.png', alt='')
    Separador 
    #t_1_2.titulo-segundo.color-acento-contenido(data-aos='fade-right')
      h2 1.2  Importancia y objetivos de la contabilidad de costos
    p.mb-4 Esta contabilidad es una variable muy importante dentro de una organización, teniendo en cuenta que:
    .row.justify-content-center.mb-5
      .col-lg-8.mb-lg-0.mb-3
        ul.lista-ul
          li.d-flex
            i.fas.fa-angle-right
            p.mb-0 Es una contabilidad analítica en la cual se pueden identificar todas las partes involucradas para dar vida a un producto o un servicio específico.
          li.d-flex
            i.fas.fa-angle-right
            p.mb-0 Los costos permiten ver con claridad cómo está la organización, su punto de partida y de llegada para ajustar algunas variables en el camino del desarrollo de la misma.
          li.d-flex
            i.fas.fa-angle-right
            p.mb-0 Contribuye a la toma de decisiones para mejorar, ver el crecimiento y la evolución de la organización en el tiempo.
          li.d-flex
            i.fas.fa-angle-right
            p.mb-0 Controla el manejo de los recursos y la forma de optimizarlos.
          li.d-flex
            i.fas.fa-angle-right
            p.mb-0 Permite a la alta gerencia poseer un mayor control sobre los recursos utilizados para el desarrollo de la actividad económica.
      .col-lg-4.col-7: img(src='@/assets/curso/temas/6.svg', alt='')
    .row.justify-content-center.mb-5
      .col-lg-5.col-7: img(src='@/assets/curso/temas/7.png', alt='')
      .col-lg-7
        p.mb-4 La contabilidad de costos persigue como objetivos principales:
        
        ol.lista-ol--cuadro.lista-ol--cuadro--separador
          li.d-flex
            .lista-ol--cuadro__vineta
              span A
            p.mb-0 Planificar y controlar las operaciones y los costos.
          li.d-flex
            .lista-ol--cuadro__vineta
              span B
            p.mb-0 Determinación del costo unitario y su valoración (ya sea bienes o servicios).
          li.d-flex
            .lista-ol--cuadro__vineta
              span C
            p.mb-0 Servir de herramienta administrativa para la toma de decisiones.
          li.d-flex
            .lista-ol--cuadro__vineta
              span D
            p.mb-0 Facilitar el control, asignación y optimización de recursos.
          li.d-flex
            .lista-ol--cuadro__vineta
              span E
            p.mb-0 Es una herramienta para la elaboración de presupuestos (Emprendefx.com,s.f.,p.).


</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({
    mostrarIndicadorTarjetaAudio: true,
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
