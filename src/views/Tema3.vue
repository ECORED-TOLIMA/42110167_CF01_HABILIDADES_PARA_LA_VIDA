<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 3
      h1 Necesidades humanas

    p Las necesidades humanas no solo deben entenderse como carencias o como la falta de algo. También pueden comprenderse como potencialidades que motivan y movilizan a las personas a actuar, relacionarse y desarrollarse.

    .row.align-items-center.justify-content-center
      .col-lg-12
        .row.justify-content-center.mt-4
          .col-lg-12(data-aos="fade-down")
            .row.d-flex.align-items-center.bg-1.bg-r8(data-aos="fade-right")
              .col-lg.p-4
                p Por ejemplo, la necesidad de afecto no solo implica la ausencia de relaciones, sino también la capacidad de dar y recibir afecto. De igual manera, la necesidad de participación impulsa a las personas a involucrarse activamente en su entorno.

                p Desde esta perspectiva, más que “satisfacer” necesidades, se trata de vivirlas y desarrollarlas de manera continua en la vida cotidiana. Entenderlas de esta forma permite reconocer al ser humano de manera integral y evitar una visión limitada de su desarrollo.
              .col-lg-auto.pe-lg-0.mb-4.mb-xl-0.d-flex.d-none.d-lg-block
                figure.m-0.p-0.w-100.h-100.d-flex
                  img(src='@/assets/curso/temas/tema3/1.svg', alt='', class="w-100 h-100 object-fit-cover")



    separador
    #t_3_1.titulo-segundo.color-acento-contenido
      h2 3.1. Necesidades axiológicas y existenciales

    p Las necesidades humanas no se relacionan únicamente con lo material o económico. También están vinculadas con aspectos personales, sociales y emocionales que influyen directamente en el bienestar de las personas. 

    p Desde el enfoque de Desarrollo a Escala Humana, estas necesidades pueden comprenderse a partir de dos dimensiones que se relacionan entre sí: 

    .row.justify-content-center.mt-4
      .col-lg-10
        .row.align-items-center.bg-3.p-4
          p Las necesidades axiológicas, que hacen referencia a aspectos fundamentales para la vida, como la subsistencia, la protección, el afecto, el entendimiento, la participación, el ocio, la creación, la identidad y la libertad. 

          p Las necesidades existenciales, que se expresan en cuatro dimensiones presentes en la vida cotidiana:


    .tarjeta--container.row.mb-5.mt-4
      .col-md.tarjeta.bg-base.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema3/2.svg', alt='Texto que describa la imagen')          
        p #[b • Ser:] se refiere a las cualidades personales, valores, actitudes y la forma de ser de cada persona.

        p Por ejemplo, cuando una persona desarrolla motivación para aprender algo nuevo.
      
      .col-md.tarjeta.bg-4.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema3/3.svg', alt='Texto que describa la imagen')          
        p #[b • Tener:] está relacionado con los recursos, conocimientos, derechos y apoyos con los que cuenta una persona. 

        p Por ejemplo, disponer de herramientas o habilidades que permiten avanzar en un proyecto


      .col-md.tarjeta.bg-5.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema3/4.svg', alt='Texto que describa la imagen')          
        p #[b • Hacer:] se relaciona con las acciones, decisiones y actividades que se realizan en la vida diaria. 

        p Por ejemplo, participar en un curso o desarrollar una actividad que fortalezca una habilidad.

      
      .col-md.tarjeta.bg-6.p-5
        .row.justify-content-center.mb-4
          .col-6
            figure
              img(src='@/assets/curso/temas/tema3/5.svg', alt='Texto que describa la imagen')          
        p #[b • Estar:] tiene que ver con los espacios, entornos y relaciones en los que se desenvuelve una persona. 

        p Por ejemplo, compartir en un entorno familiar o comunitario que brinde apoyo.


    .row.justify-content-center.mt-4
      .col-lg-10
        p Estas dimensiones no se presentan de manera aislada, sino que están interconectadas y se manifiestan constantemente en la vida cotidiana. Comprenderlas permite analizar de manera más amplia cómo se construye el bienestar.

        p Las necesidades humanas son universales; sin embargo, las formas de satisfacerlas, llamadas satisfactores, varían según la cultura, la historia y las condiciones de cada persona o comunidad.

        p Un mismo satisfactor puede responder a varias necesidades, y una necesidad puede satisfacerse de diferentes maneras. Por ejemplo, participar en un espacio comunitario puede aportar al mismo tiempo al afecto, la participación y la identidad.


    .bloque-texto-g.bloque-texto-g--inverso.bg-base.p-3.p-sm-4.p-md-5.mt-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema3/6.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 Los bienes económicos pueden apoyar la satisfacción de las necesidades, pero no son las necesidades en sí mismas. En algunos casos, contribuyen al bienestar; sin embargo, cuando se convierten en un fin, pueden afectar la forma en que las necesidades se satisfacen.<br><br>

        p Comprender estas relaciones permite reflexionar sobre cómo se viven y se satisfacen las necesidades en la vida cotidiana, más allá de lo económico.


    separador
    #t_3_2.titulo-segundo.color-acento-contenido
      h2 3.2. Matriz de necesidades (referente general)

    p A continuación, se presenta una matriz general que permite comprender cómo se relacionan las necesidades humanas con las dimensiones de la vida cotidiana. Esta matriz es un referente que facilita el análisis de situaciones reales y sirve como base para el desarrollo de las actividades del curso:


    .row.justify-content-center.mb-5(data-aos="flip-up")
      .col-12
        .titulo-sexto.color-acento-contenido
          h5 Tabla 1.
          span Matriz de necesidades (referente general)
        .tabla-a.clstabla.color-acento-contenido.mb-5 
          table
            thead
              tr
                td.text-bold.text-center Necesidades axiológicas
                td.text-bold.text-center Ser 
                td.text-bold.text-center Tener 
                td.text-bold.text-center Hacer 
                td.text-bold.text-center Estar
            tbody
              tr(style="background-color: #F6F6F6")
                td Subsistencia.
                td Cuidado personal, salud.
                td Alimentación, vivienda.
                td Alimentarse, descansar.
                td Entorno saludable.
              tr
                td Protección.
                td Seguridad, confianza.
                td Redes de apoyo, servicios.
                td Prevenir, cuidar.
                td Hogar, comunidad.

              tr(style="background-color: #F6F6F6")
                td Afecto.
                td Respeto, empatía.
                td Familia, amistades.
                td Compartir, expresar.
                td Espacios de encuentro.

              tr
                td Entendimiento.
                td Curiosidad, pensamiento crítico.
                td Educación, información.
                td Aprender, analizar.
                td Espacios educativos.

              tr(style="background-color: #F6F6F6")
                td Participación.
                td Responsabilidad, compromiso.
                td Derechos, oportunidades.
                td Opinar, decidir.
                td Comunidad, grupos.




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
