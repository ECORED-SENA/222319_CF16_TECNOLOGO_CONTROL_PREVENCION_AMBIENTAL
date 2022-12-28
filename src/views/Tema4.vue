<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Actores sociales

    p.mb-4 En una sociedad constituida por diferentes tipos de personas, donde se destacan tanto los hombres como las mujeres, los niños y niñas, la familia, la comunidad, entre otros, es importante reconocer cómo se clasifican los diferentes actores que hacen parte de este ecosistema social en el que se vive.

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/img1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La identificación de la población y, de manera simultánea, <b>la identificación de necesidades de capacitación por tipo de población,</b> para la aplicación de las estrategias de la campaña ambiental, se convierten en objetivo fundamental de trabajo porque el éxito del proceso depende, en mayor proporción, de la comunidad misma, de las formas organizativas que ella tenga y del territorio y contexto que habita. 
    separador 

    #t_4_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 4.1	¿Qué es un actor social?

    p.mb-4 Un actor social es un sujeto naturalmente configurado para vivir en colectivo, pero estructurado a partir de una conciencia de identidad propia individual; es un portador de valores, poseedor de un cierto número de recursos que le permiten actuar en el seno de una sociedad, con vistas a defender los intereses de los miembros que la componen y/o de los individuos que representa, para dar respuesta a las necesidades identificadas como prioritarias. Se incluyen:

    .row.mb-4
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema4/1.png', alt='Texto que describa la imagen')
          h4.text-center Grupo e individuos
          p.mb-0 También puede ser entendido como un grupo de intervención, que percibe a sus miembros como productores de su historia, para la transformación de su situación. 
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema4/2.png', alt='Texto que describa la imagen')
          h4.text-center Acción bidireccional
          p.mb-0 O sea que el actor social actúa sobre el exterior, pero también sobre sí mismo. En ambos casos, el actor se ubica como sujeto colectivo, entre el individuo y el Estado. 
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema4/3.png', alt='Texto que describa la imagen')
          h4.text-center Sujetos aportantes
          p.mb-0 En dicho sentido, es generador de estrategias de acción (acciones sociales), que contribuyen a la gestión y transformación de la sociedad. (Touraine, 1984).
    separador

    #t_4_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 4.2	Caracterización

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema4/img2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Para realizar una respectiva identificación de los diversos actores sociales y sus potenciales aportes a la campaña ambiental, es importante tener en cuenta las siguientes características. Con ellas es más fácil evaluar a los actores que habría en las comunidades; dicho de otra manera, se trata de definir quién hace qué, en nombre de quién, cómo, con qué objetivo, con quién y con qué resultados. Lo que esto busca es detectar el tipo e intensidad de las relaciones establecidas entre los actores sociales, así como los modos de relación (desde los más conflictivos a los más consensuales), con la finalidad de definir los ejes prioritarios de la acción social, los factores de bloqueo y las posibilidades de resolución de los conflictos.   

    .row.justify-content-center.mb-4
      .col-lg-10
        .row.align-items-center
          .col-lg-6
            figure.mb-2
              img(src='@/assets/curso/tema4/4.png', alt='Texto que describa la imagen')
          .col-lg-6
            p.mb-4 Según Kullock et al. (1993), se tiene en cuenta:
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-0 Su campo de intervención. 
              li 
                i.fas.fa-check
                p.mb-0 La función que cumplen. 
              li 
                i.fas.fa-check
                p.mb-0 Su representatividad, el poder que invisten. 
              li 
                i.fas.fa-check
                p.mb-0 Los recursos de que disponen. 
              li 
                i.fas.fa-check
                p.mb-0 Los objetivos que persiguen. 
              li 
                i.fas.fa-check
                p.mb-0 Las acciones que desarrollan.
              li 
                i.fas.fa-check
                p.mb-0 Los resultados que obtienen. 
              li 
                i.fas.fa-check
                p.mb-0 Las relaciones tejidas con otros actores para llevar a cabo sus estrategias.
    separador 

    #t_4_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 4.3	El actor social y el contexto

    p.mb-4 Los actores sociales dependen en gran medida del contexto en el que se desarrollan; su idiosincrasia y cultura marcan una tendencia específica en los tipos de actores que se encuentran en una población; entre ellos están:

    AcordionA(tipo="a" clase-tarjeta="tarjeta color-3")
      .row(titulo="Organizaciones comunitarias y juntas vecinales")
        .col-md-3
          figure
            img(src='@/assets/curso/tema4/acor1.png', alt='Texto que describa la imagen')
        .col-md-9
          p Las organizaciones comunitarias de base son la forma asociativa más representativa de los habitantes y en las cuales las actividades se focalizan en el mejoramiento de las condiciones de vida existentes (clubes de madres, asociaciones de jóvenes, asociaciones de padres, y otras). En el mismo sentido, las juntas vecinales constituyen la organización representativa de un sector ante las autoridades administrativas competentes y se ven, así, encargadas por el poder político de las negociaciones entre el sector público y los habitantes.
        
      .row(titulo="Las ONG y los colectivos emprendedores")
        .col-md-3
          figure
            img(src='@/assets/curso/tema4/acor2.png', alt='Texto que describa la imagen')
        .col-md-9
          p Las Organizaciones No Gubernamentales defienden ciertos derechos de los habitantes (de carácter humanitario, económico, cultural o político) y se constituyen en grupos de presión ante las instancias involucradas. Por su parte, los colectivos emprendedores son individuos o asociaciones que gerencian el desarrollo e implementación de proyectos y/o emprendimientos, motivo de las EIA y defienden sus intereses de grupo.

      .row(titulo="Grupos de presión coyuntural y agrupaciones políticas")
        .col-md-3
          figure
            img(src='@/assets/curso/tema4/acor3.png', alt='Texto que describa la imagen')
        .col-md-9
          p Los grupos de presión de carácter coyuntural se caracterizan por su existencia transitoria en relación con un problema limitado en su extensión y en el tiempo, mientras que las agrupaciones políticas defienden a sus afiliados sobre la base de valores ideológicos (construcción teórica de la sociedad y de su evolución), dando lugar a acciones tendientes a hacer evolucionar la organización social en relación con sus valores y con los fines defendidos.
        
      .row(titulo="Propietarios de bienes raíces y agentes inmobiliarios")
        .col-md-3
          figure
            img(src='@/assets/curso/tema4/acor4.png', alt='Texto que describa la imagen')
        .col-md-9
          p En tanto los propietarios de bienes raíces son los poseedores de parcelas y de los inmuebles potencialmente afectados en procesos o situaciones diversas, los agentes inmobiliarios operan en el mercado de las propiedades urbanas y rurales.

      .row(titulo="El sector financiero")
        .col-md-3
          figure
            img(src='@/assets/curso/tema4/acor5.png', alt='Texto que describa la imagen')
        .col-md-9
          p Se trata de la banca hipotecaria, mutuales, cooperativas de crédito y de ahorro, banca comercial; quienes juegan un rol de intermediación del crédito ante el público.
       
      .row(titulo="El sector público y los sindicatos")
        .col-md-3
          figure
            img(src='@/assets/curso/tema4/acor6.png', alt='Texto que describa la imagen')
        .col-md-9
          p El sector público son todos aquellos operadores principales en materia de planificación, programación, gestión, supervisión y fiscalización; tienen, en principio, la función de implementar las reglamentaciones y propender al bien común. Por su parte, los sindicatos tienen por objetivo la defensa de los intereses económicos y sociales de los trabajadores incluidos en un mismo rubro de actividades productivas.

      .row(titulo="Promotores ambientales")
        .col-md-3
          figure
            img(src='@/assets/curso/tema4/acor7.png', alt='Texto que describa la imagen')
        .col-md-9
          p Buscan optimizar la relación de la intervención propuesta con el medio ambiente. (Kullock et al., 1993)
       





</template>

<script>
export default {
  name: 'Tema4',
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
