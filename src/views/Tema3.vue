<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 3
      h1 Métodos contemporáneos de enseñanza

    p.mb-4 Las nuevas tendencias en enseñanza, y tomando como referencia la tecnología que avanza a pasos agigantados de la mano a las nuevas formas de comunicación, llevan a concebir actualizadas metodologías, dentro de las que se encuentran:

    .row.justify-content-center.mb-4
      .col-lg-10
        .row.align-items-center
          .col-lg-6
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-0 Aprendizaje basado en proyectos.
              li 
                i.fas.fa-check
                p.mb-0 Aprendizaje basado en problemas.
              li 
                i.fas.fa-check
                p.mb-0 Flipped classroom (aula invertida).
              li 
                i.fas.fa-check
                p.mb-0 Pensamiento de diseño (design thinking).
              li 
                i.fas.fa-check
                p.mb-0 Gamificación.
              li 
                i.fas.fa-check
                p.mb-0 Aprendizaje basado en el pensamiento (thinking based learning).
              li 
                i.fas.fa-check
                p.mb-0 Aprendizaje cooperativo.
              li 
                i.fas.fa-check
                p.mb-0 Método Montessori.
          .col-lg-6
            figure.mb-2
              img(src='@/assets/curso/tema3/1.png', alt='Texto que describa la imagen')

    .row.justify-content-center.mb-4 
      .col-lg-8
        .tarjeta.colordegra.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/curso/tema1/you.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4.mb-1 Cursos on-line masivos. (2018). Métodos de enseñanza
                  p  Acceda al vídeo que aquí se propone y refuerce los elementos que le contextualizan mejor, el contenido de este punto.
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema3/img1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Lo dicho hasta aquí confirma que la educación va dirigida a diversas poblaciones, no solo infantil y adolescente, sino también a población de mayores y adultos mayores. <b>¡Cuánto más la educación ambiental!</b> Gracias al acceso generalizado a la información, la educación, con cualquier enfoque, va siendo concebida de otras maneras. Según Area y Adell (2009, p. 2), en estos momentos, el campo de la educación superior, de la educación de personas adultas, de la formación en los ámbitos empresariales y de formación ocupacional, de las enseñanzas medias, entre otros, ofrecen sus cursos no sólo en las modalidades tradicionales de aulas físicas, sino también a través de lo que se conoce como aulas virtuales.

    p.mb-4 Algunos métodos son:

    AcordionA(tipo="a" clase-tarjeta="tarjeta color-3")
      .row(titulo="El e-learning")
        .col-md-3
          figure
            img(src='@/assets/curso/tema3/tab1.png', alt='Texto que describa la imagen')
        .col-md-9
          p El concepto de e-learning (o de otros similares, como teleformación, educación virtual, cursos online, enseñanza flexible, educación web, docencia en línea, entre otros ) es una modalidad de enseñanza-aprendizaje que consiste en el diseño, puesta en práctica y evaluación de un curso o plan formativo desarrollado a través de redes de ordenadores, y puede definirse como una educación o formación ofrecida a individuos que están geográficamente dispersos o separados o que interactúan en tiempos diferidos del docente, empleando los recursos informáticos y de telecomunicaciones. (Area y Adell, 2009, p. 2).
        
      .row(titulo="Versatilidad educativa")
        .col-md-3
          figure
            img(src='@/assets/curso/tema3/tab2.png', alt='Texto que describa la imagen')
        .col-md-9
          p El avance tecnológico y el crecimiento de la tendencia en educación virtual lleva al e-learning a convertirse, de ahora en adelante, en la herramienta más versátil, económica y, sobre todo, accesible para todos; por eso, los aportes de enseñanza se pueden enmarcar en el contexto del avance y las nuevas revoluciones educativas.

      .row(titulo="Los aportes del e-learning")
        .col-md-3
          figure
            img(src='@/assets/curso/tema3/tab3.png', alt='Texto que describa la imagen')
        .col-md-9
          p Con las nuevas modalidades de enseñanza-aprendizaje, es cada vez más factible extender y facilitar el acceso a la formación de colectivos e individuos que no pueden acceder a la modalidad presencial. También se incrementa la autonomía y responsabilidad del estudiante en su propio proceso de aprendizaje. De la misma manera, es cada vez más posible superar las limitaciones provocadas por la separación en espacio y/o tiempo de profesor-alumnos.
        
      .row(titulo="Virtualidad colaborativa")
        .col-md-3
          figure
            img(src='@/assets/curso/tema3/tab4.png', alt='Texto que describa la imagen')
        .col-md-9
          p La virtualización de los programas de estudio, en cualquiera de las áreas, ofrece gran potencial interactivo entre profesor-alumno. Asimismo, flexibilidad en los tiempos y espacios educativos, acceso a multiplicidad de fuentes y datos distintos a los ofrecidos por el profesor, en cualquier momento y desde cualquier lugar. Esta nueva forma favorece el aprendizaje colaborativo entre comunidades virtuales de docentes y estudiantes. (Area y Adell, 2009, p. 2).

      .row(titulo="Nuevos rumbos")
        .col-md-3
          figure
            img(src='@/assets/curso/tema3/tab5.png', alt='Texto que describa la imagen')
        .col-md-9
          p Debemos entender que el e-learning es la tendencia que cada día nos es más familiar. Esta nueva modalidad es la que va a conducir la educación por un nuevo rumbo, y cuánto mejor que sirva como herramienta para la educación ambiental, que permite llegar a toda una población o comunidad interesada por preservar el ambiente en el que vive.
        
    .row.justify-content-center.mb-4 
      .col-lg-8
        .tarjeta.colordegra.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/curso/tema1/you.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4.mb-1 Plataforma e-learning. (2017). ¿Qué es e-learning?
                  p  Para profundizar en el tema e-learning, se le invita a visitar el siguiente enlace y a observar atentamente el video:
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 


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
