<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 2
      h1 Enfoque de Desarrollo a Escala Humana (DEH)

    p El enfoque de Desarrollo a Escala Humana (DEH) propone una forma de comprender el desarrollo centrada en las personas y en su bienestar. Desde esta perspectiva, el desarrollo no se mide únicamente por lo económico, sino por las oportunidades que tienen las personas para satisfacer sus necesidades y mejorar su calidad de vida.

    p Este enfoque resalta que existe una relación directa entre el bienestar y la forma en que se satisfacen las necesidades humanas. Estas necesidades incluyen aspectos:

    .row.mt-4.justify-content-center
      .col-lg-5
        figure(data-aos="fade-right")
          img(src='@/assets/curso/temas/tema2/1.png')
        
        p.mt-2 • Tangibles, como la alimentación o la vivienda.

      .col-lg-5
        figure(data-aos="fade-right")
          img(src='@/assets/curso/temas/tema2/2.png')
        
        p.mt-2 • Intangibles, como el afecto, la participación y el aprendizaje.


    .row.justify-content-center.mt-4
      .col-lg-10
        .row.align-items-center
          .col-lg-12
            .cajon.color2.p-4
              p Las necesidades humanas fundamentales son universales; es decir, todas las personas las tienen, sin importar el lugar o la época. A lo largo de la historia, han estado presentes necesidades como la subsistencia, la protección, el afecto y la participación. Con el tiempo, otras como la identidad y la libertad han adquirido mayor relevancia en la forma en que las personas construyen su vida.

        p.mt-4 Aunque las necesidades son las mismas, la manera de satisfacerlas cambia según el contexto. Por ejemplo, la necesidad de subsistencia es común a todas las personas, pero la forma de alimentarse o de habitar un espacio varía según las condiciones culturales, sociales y territoriales.


    .bloque-texto-g.bloque-texto-g--inverso.bg-base.p-3.p-sm-4.p-md-5.mt-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema2/3.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        p.mb-0 En Colombia, estas diferencias se evidencian en la vida cotidiana. La alimentación en la Región Caribe es distinta a la de comunidades en zonas rurales o selváticas, así como las formas de vivienda cambian según el clima, el territorio y las costumbres. Esto muestra que el desarrollo no depende de tener más bienes, sino de contar con condiciones que permitan satisfacer las necesidades de manera adecuada.



    p.mt-4 Desde este enfoque, el desarrollo implica que las personas tengan la posibilidad de tomar decisiones, construir su proyecto de vida y participar activamente en su entorno. En este sentido, no basta con la existencia de normas o programas; también es necesario que las personas fortalezcan sus capacidades, utilicen su pensamiento crítico y actúen de manera consciente frente a su realidad.

    p Por ello, comprender el enfoque de Desarrollo a Escala Humana permite analizar de manera más amplia las condiciones de vida y reconocer que el bienestar se construye a partir de la relación entre las necesidades, las decisiones y las oportunidades que tienen las personas en su contexto.

    p A continuación, se presenta un ejemplo que permitirá comprender de manera más concreta cómo se expresan las necesidades humanas en la vida cotidiana.


    .row.justify-content-center.mb-4(data-aos="flip-up")
      .col-lg-10.col-12
        .titulo-sexto.color-acento-contenido
          h5 Figura 1.
          span Necesidades humanas 
      .row.justify-content-center
        .col-10
          figure.desktop
            img(src='@/assets/curso/temas/tema2/4.svg', alt='Imagen que relaciona lo que representan las necesidades humanas y explica a partir de un ejemplo su aplicación.')
      .col-12
        figure.movil
          img(src='@/assets/curso/temas/tema2/5.svg', alt='')



















      


</template>

<script>
export default {
  name: 'Tema2',
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
