<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 5
      h1 Competencias socioemocionales
    
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-7.order-lg-1.order-2(data-aos="fade-left")
        .bloque-texto-d.color-primario.p-4.mb-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left(style="color:#E6D09E")
            p Para satisfacer sus necesidades fundamentales, las personas desarrollan competencias socioemocionales que les permiten comunicarse, tomar decisiones éticas, fortalecer la autoestima, ser resilientes ante los imprevistos, trabajar en equipo y regular sus emociones en las relaciones personales y sociales.
            i.fas.fa-quote-right(style="display:none")
          .bloque-texto-d__autor
            .h5.mb-0 (Ricouer, citado en Raciti, 2016). 
              i.fas.fa-quote-right(style="color:#E6D09E")
        p.mb-2 Estas competencias no funcionan de manera aislada, sino que requieren un equilibrio cultural que favorezca la interacción con el mundo, con los demás y consigo mismo.
        p.mb-0 La satisfacción de las necesidades humanas, impulsa a las personas a buscar tanto su bienestar, como el de su comunidad. En este sentido, los constructos socioemocionales deben reconocerse como una parte esencial de la naturaleza humana, ya que permiten expresar y gestionar deseos y aspiraciones en el ámbito de las relaciones humanas y en conexión con el medio ambiente. Al respecto, analice la siguiente jerarquía:
      .col-lg-5.col-10.mb-lg-0.mb-4.order-lg-2.order-1(data-aos="fade-right")
        img(src='@/assets/curso/temas/tema5/img_1.png', alt='Imagen decorativa')

    .row.justify-content-center.mb-5(data-aos="fade-down")
      .col-lg-9.col-12.mb-4.mb-lg-2
        .titulo-sexto.color-acento-contenido
          p.titulo.pb-0.mb-0 <b>Figura 2.</b> <i>Jerarquía necesidades humanas</i>
        figure
          img(src='@/assets/curso/temas/tema5/fig-2a.svg', alt='Imagen que relaciona una matriz que representa de manera jerárquica las necesidades humanas, como son competencia, habilidad, destreza y conducta.')  
          figcaption Nota. Adaptado de Raciti (2016)


    p.mb-5(data-aos="fade-right") Según Raciti (2016), las competencias son habilidades, destrezas y conductas que pueden observarse, como conocimientos técnicos y comportamientos, o inferirse, como valores, resiliencia o gestión de emociones. Estas competencias se organizan en dos categorías: 

    .row.justify-content-center.mb-5
      .col-lg-5.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar-b.mb-4
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema5/icoA.svg' alt='Imagen decorativa')
          .tarjeta.BGR01.p-4
            h4.ps-5 Fundantes
            p.ps-5.mb-0 Relacionadas con el ser.

      .col-lg-5.mb-lg-0.mb-4(data-aos="fade-right")
        .tarjeta-avatar-b
          .tarjeta-avatar-b__img
            img(src='@/assets/curso/temas/tema5/icoB.svg' alt='Imagen decorativa')
          .tarjeta.BGR01.p-4
            h4.ps-5 Integradoras
            p.ps-5.mb-0 Relacionadas con el hacer.

    .bloque-texto-g.bloque-texto-g--inverso.color-primario.mb-5.p-3.p-sm-4.p-md-5(data-aos="fade-down")
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/temas/tema5/img_2.png')})`}"
      )
      .bloque-texto-g__texto.p-4
        h4.mb-0 Competencias socioemocionales (CSE)
        br
        br
        p.mb-0 Son conocimientos, habilidades y destrezas que ayudan a las personas a interactuar con otros, resolver problemas y alcanzar objetivos de forma autónoma y eficaz. Estas influyen en cómo se piensa, siente y se comunica para enfrentar los retos diarios.

    p.mb-5(data-aos="fade-right") A continuación, se explican dichas categorías:

    TabsC.mb-5(data-aos="fade-down")
      .p-4.p-lg-5(titulo="CSE del ser (fundantes)")
        .row.justify-content-center.px-lg-0.px-3
          .col-12.col-lg-8.mb-3
            figure
              img(src='@/assets/curso/temas/tema5/img-1A.png', alt='Imagen decorativa')
          .col-12.col-lg-4
            p.mb-0 Son la base emocional y personal de cada individuo. Incluyen autoestima, resiliencia, regulación emocional y capacidad de comunicación. Estas competencias son esenciales para la conexión con uno mismo, los demás y el mundo.
      .p-4.p-lg-5(titulo="CSE del hacer (integradoras)")
        .row.justify-content-center.px-lg-0.px-3
          .col-12.col-lg-8.mb-3
            figure
              img(src='@/assets/curso/temas/tema5/img-1B.png', alt='Imagen decorativa')
          .col-12.col-lg-4
            p.mb-0 Están relacionadas con las acciones que las personas realizan para resolver problemas y alcanzar metas, conectando lo que son con lo que hacen.

    p.mb-5(data-aos="fade-right") Estas competencias se reinterpretan a partir de la matriz del Desarrollo a Escala Humana (DEH), integrándose como herramientas esenciales para satisfacer necesidades fundamentales y construir una vida plena y equilibrada.
    p.mb-5(data-aos="fade-right") De acuerdo a dichas categorías, hacen parte de las competencias fundantes: autoestima, empatía, regulación emocional, resiliencia y comunicación, las cuales se explican a continuación:

    .row.justify-content-center.p-4(data-aos="zoom-in-right")
      .titulo-sexto.color-acento-contenido
        p.pb-0.mb-0 <b>Tabla 15. </b> <em>Matriz de relación competencias fundantes y necesidades existenciales y axiológicas</em>
      .tabla-a.color-acento-contenido.mb-5
        table(alt="Tabla que relaciona las competencias fundantes y sus necesidades existenciales y axiológicas.")
          thead
            tr.text-center
              th(rowspan="2") Competencias fundantes
              th(colspan="4") Necesidades existenciales
              th(rowspan="2") Necesidades axiológicas
            tr.bg-tb-2
              td #[strong Ser] (Lo que tengo que ser para cumplir esa necesidad) 
              td #[strong Tener] (Lo que tengo que tener para cumplir esa necesidad)
              td #[strong Hacer] (Lo que tengo que hacer para cumplir esa necesidad)
              td #[strong Estar] (En donde puedo cumplir esa necesidad) 
          tbody
            tr
              th Autoestima
              td Exploro mis fortalezas, debilidades, sueños, metas, intereses y aspectos a mejorar, como elementos de reconocimiento en la construcción de mi trayectoria de vida.
              td Desarrollo herramientas para priorizar y atender las necesidades de mi vida.
              td Fortalezco mis potencialidades y construyo una trayectoria de vida con la que me sienta realizado.
              td Comparto con personas que me permiten fortalecer mi autoestima en entornos familiares, sociales, laborales, educativos.
              td Afecto, entendimiento, participación, creación, identidad, libertad.
            tr
              th Empatía
              td Me conecto emocionalmente con el otro entendiendo sus necesidades y puntos de vista.
              td Desarrollo capacidades para identificar diferentes perspectivas reconociendo al otro, sus pensamientos y sentimientos.
              td Reconozco los sentimientos y la perspectiva o punto de vista u opinión de otras personas y respeto las diferencias entre lo que cada uno siente respecto a las mismas cosas.
              td En los diferentes espacios en los que interactúo, trato de entender los puntos de vista y el sentimiento de los demás.
              td Afecto, entendimiento, identidad, participación, libertad.
            tr
              th Regulación emocional
              td Desarrollo procesos de autoconocimiento que me permitan identificar mis emociones y la manera en que las puedo regular.
              td Utilizo herramientas de identificación y manejo de emociones en la vida personal y en la interacción con los otros.
              td Aprendo a ejercen una influencia sobre las emociones que experimento, sobre cuando suceden y sobre cómo se experimentan y se expresan.
              td En los espacios en los que participo, promuevo la expresión y manejo de las emociones individuales y colectivas, de una manera constructiva.
              td Subsistencia, protección, afecto, participación, identidad, libertad.
            tr
              th Resiliencia
              td Identifico en mi la característica que me han permitido superar las situaciones difíciles.
              td Reconozco los mecanismos que me han permitido superar la adversidad a mí y a otros.
              td Pongo en práctica acciones que potencien mis fortalezas y me ayuden a superar las adversidades.
              td Creo espacios con mi entorno familiar y mis amigos, que me permitan consolidar percepciones optimistas del futuro.
              td Subsistencia, protección, participación, identidad.
            tr
              th Comunicación
              td Identifico mis habilidades para intercambiar información con otros con el fin de comunicar mis pensamientos, sentimientos y opiniones.
              td Uso formas de comunicación basadas en el respeto y control emocional que me permiten exponer claramente mis ideas y puntos de vista.
              td Aprendo a expresarme verbal y no verbalmente en la interacción con el otro.
              td Creo y participo en espacios donde puedo intercambiar opiniones de una manera asertiva.
              td Afecto, entendimiento, participación, identidad.


    .row.justify-content-center.align-items-center.mb-4(data-aos="zoom-in-down")
      .col-lg-8.order-lg-1.order-2
        p.mb-2 Las CSE articuladas bajo la categoría existencial del hacer se pueden definir como competencias integradoras, en la medida en que se expresan a través de la interacción entre varias competencias fundantes.
        .cajon.cajon1.color-primario.p-4
          p.mb-0 Las competencias CSE integradoras combinan las competencias fundantes y habilidades técnicas específicas para facilitar la acción y expresión en diferentes contextos. Estas competencias permiten a las personas satisfacer sus necesidades existenciales de creación y participación, promoviendo su interacción con el entorno y con los demás.
      .col-8.col-lg-4.order-lg-2.order-1.mb-5.mb-lg-0
        img(src='@/assets/curso/temas/tema5/img-3.png', alt='Imagen decorativa')

    p.mb-5(data-aos="fade-right") Y como segunda categoría, hacen parte de las competencias integradoras: liderazgo, gestión del conflicto, trabajo en equipo y toma de decisiones, las cuales se explican a continuación:


    .row.justify-content-center.p-4(data-aos="zoom-in-right")
      .titulo-sexto.color-acento-contenido
        p.pb-0.mb-0 <b>Tabla 16. </b> <em>Matriz de relación competencias estratégicas y necesidades existenciales y axiológicas</em>
      .tabla-a.color-acento-contenido.mb-5
        table(alt="Tabla que relaciona las competencias estratégicas y sus necesidades existenciales y axiológicas.")
          thead
            tr.text-center
              th(rowspan="2") Competencias integradoras 
              th(colspan="4") Necesidades existenciales
              th(rowspan="2") Necesidades axiológicas
            tr.bg-tb-2
              th Ser
              th Tener
              th Hacer
              th Estar
          tbody
            tr
              th Liderazgo
              td Me empodero de mis deseos, sueños, anhelos y planteó mi trayectoria de vida como ser transformador y visionario. 
              td Desarrollo capacidades para relacionarme con otras personas y actuar como agente de cambio.  
              td Genero procesos de transformación de mi entorno desde acciones personales y colectivas.
              td 
                p Promuevo y participo en escenarios de empoderamiento individual y colectivo, siendo. 
                p.mb-0 Corresponsable en la transformación de mi entorno.
              td Entendimiento, participación, creación, libertad.
            tr
              th Gestión del conflicto
              td Potencio mi capacidad de diálogo, desde la tolerancia y la identificación de las múltiples perspectivas de interpretar el mundo, en las que priman el reconocimiento de los derechos del otro. 
              td Reconozco las fuentes de conflicto y sus efectos en la convivencia, para aprender a partir de la experiencia en el relacionamiento con los demás. 
              td Realizo acciones de promoción de la convivencia pacífica y prevención de violencia, mejorando mi capacidad de respuesta ante escenarios desafiantes.
              td Construyo espacios de vida libres de estrés y violencia, con estrategias alternas para manejo de desacuerdos y conﬂictos.
              td Participación, entendimiento, creación, libertad.
            tr
              th Trabajo en equipo
              td Fortalezco mi pensamiento creativo y capacidad de adaptación, para responder de manera flexible y responsable en actividades y funciones con diferentes personas en búsqueda de un propósito común. 
              td Reconozco la importancia de mi aporte al cumplimiento de los objetivos planteados desde diferentes roles que puedo asumir, en los distintos contextos en los que me desenvuelvo.  
              td Asumo mi rol en las tareas que me son encomendadas como integrante en procesos colaborativos y de trabajo.
              td Participo en escenarios que me permiten relacionarme de manera colaborativa con otros y aportar al cumplimiento de objetivos comunes.
              td Participación, entendimiento, creación, libertad.
            tr
              th Toma de decisiones
              td Reconozco la importancia de escucharme y escuchar a las personas en las que confió para elegir la opción más adecuada en mi vida personal y comunitaria.  
              td Realizo ejercicios de reﬂexión individual y colectiva que me permitan aportar en la definición de alternativas de acción. 
              td Implemento acciones que me permiten analizar situaciones y elegir la opción más adecuada.
              td Hago parte de escenarios en los que puedo contribuir en decisiones que me afectan de manera individual o colectiva.
              td Participación, entendimiento, creación, libertad.



</template>

<script>
export default {
  name: 'Tema5',
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
