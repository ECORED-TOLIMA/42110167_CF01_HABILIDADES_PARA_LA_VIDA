<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    p Este componente tiene como objetivo que los aprendices identifiquen los fundamentos del enfoque de Desarrollo a Escala Humana (DEH), comprendiendo su relación con las necesidades humanas y su importancia como base para el desarrollo de competencias socioemocionales.

    .row.justify-content-center.mt-4
      .col-lg-10
        .row.align-items-center
          .col-lg-12
            .cajon.color2.p-4
              p En este componente formativo se presenta el enfoque de Desarrollo a Escala Humana (DEH) como una manera de comprender el desarrollo centrada en las personas y en su bienestar. Este enfoque propone que el desarrollo no depende únicamente de lo económico, sino de la forma en que las personas satisfacen sus necesidades y construyen su vida en relación con otros y con su entorno.

    .row.fondo-1.px-md-5.px-4.justify-content-center.align-items-center.mb-5.mt-4
      .col-lg-5.col-10.mb-4.mb-lg-0(data-aos="fade-right")
        img(src='@/assets/curso/temas/img_1.png', alt='')
      .col-lg-5(data-aos="fade-left")
        p Desde esta perspectiva, el ser humano se entiende como un ser integral, que se desarrolla a partir de la interacción entre sus dimensiones personales, sociales y emocionales, y de las decisiones que toma en su vida cotidiana.

        p A lo largo de la vida, las personas enfrentan situaciones que implican tomar decisiones, relacionarse con otros y responder a diferentes retos. Estas experiencias influyen en la forma en que piensan, sienten y actúan, y están relacionadas con su contexto familiar, social y cultural.

        p Por esta razón, es importante fortalecer competencias que permitan mejorar la relación consigo mismo, con los demás y con el entorno. Estas competencias facilitan la toma de decisiones, la resolución de situaciones cotidianas y la construcción de relaciones más positivas.

    .row.justify-content-center.mt-4
      .col-lg-10
        p.bg-1.p-4 Con el fin de facilitar la comprensión general del enfoque, se sugiere analizar el siguiente recurso audiovisual, el cual presenta de manera introductoria los principales elementos del Desarrollo a Escala Humana. 

        p Este recurso permite reconocer de manera general cómo las necesidades humanas, los satisfactores y las competencias socioemocionales se relacionan en la vida cotidiana.

    .bloque-texto-g.bloque-texto-g--inverso.bg-base.p-3.p-sm-4.p-md-5.mt-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/intro/1.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En este componente se abordan los principales elementos del enfoque de Desarrollo a Escala Humana, como las necesidades humanas, sus diferentes formas de expresión y los satisfactores.<br><br>

        p Asimismo, se establece la relación entre estos elementos y las competencias socioemocionales, las cuales permiten a las personas comprender su realidad y generar acciones de mejora en su vida cotidiana.

    .row.justify-content-center.mt-4
      .col-lg-10
        p De esta manera, el contenido de este componente se orienta no solo a la comprensión de conceptos, sino también a su aplicación en situaciones reales, en coherencia con las actividades propuestas en el programa de formación:


    figure.mb-5.mt-4(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/eoo6f08n6Tw?si=pYxl1IBwwuusfX55" title="Fundamentos del enfoque Desarrollo a Escala Humana" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    
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
