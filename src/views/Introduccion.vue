<template lang="pug">
.curso-main-container.introduccion
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
  
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span
          i.fas.fa-info
      h1 Introducción

    .row.fondo-1.px-md-5.px-4.justify-content-center.align-items-center.mb-5
      .col-lg-5.col-10.mb-4.mb-lg-0(data-aos="fade-right")
        img(src='@/assets/curso/temas/img_1.png', alt='')
      .col-lg-5(data-aos="fade-left")
        p.mb-3 En este componente formativo se desarrolla el enfoque Desarrollo a Escala Humana (DEH), como una manera de ver el desarrollo y siendo el protagonista el ser humano y la satisfacción de sus necesidades humanas fundamentales, lo cual es basado en Max-Neef, Elizalde & Hopenhayn (1986); concibiéndolo como un ser integral que está en una continua persecución de equilibrio entre lo espiritual, lo psicológico, lo físico y su interacción permanente consigo mismo y con su entorno.
        p.mb-0 Lo anterior, lo complementa Savater (1991), al indicar que en el devenir de la vida, el humano continuamente se enfrenta a diferentes condiciones que generan emociones y comportamientos que llevan a escoger entre diversas opciones, las cuales están enmarcadas en los valores y concepciones adquiridas en la experiencia, del deber ser, de la cultura, la familia y el contexto en el que está involucrado, por lo que tendrá que discernir entre lo “bueno y lo malo”, “lo correcto e incorrecto”; así como afrontar situaciones difíciles que pondrán a prueba su resiliencia y capacidad para sobreponerse y encontrar las fortalezas personales que le permitirán salir adelante. 

    p.mb-3(data-aos="fade-left") Es por esto, que se requiere el desarrollo de competencias que permitan la mejora personal en cuanto a la convivencia consigo mismo y con el otro, donde se desarrolle empatía, resiliencia, autoestima y pensamientos positivos, se aprenda a trabajar en equipo, gestionar conflictos, tomar decisiones que permitan ver soluciones y propuestas de mejora para sí mismo y para poder crear sociedad.

    p.mb-5(data-aos="fade-left") Basado en la descripción anterior, es importante que acceda al siguiente video, para comprender la importancia del contenido y los diferentes temas:

    figure.mb-5(data-aos="zoom-in")
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/8DU5V_30RYg" title="Fundamentos del enfoque Desarrollo a Escala Humana" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)

    
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
