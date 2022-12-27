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
          h4.text-center Proceso natural
          p.mb-0 Por lo tanto, la comunicación es un fenómeno inherente a la relación que los seres vivos mantienen cuando se encuentran en grupo.
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema4/2.png', alt='Texto que describa la imagen')
          h4.text-center Proceso dinámico
          p.mb-0 La comunicación es un proceso que se inicia en la intención de una persona, quien construirá un mensaje y lo transmitirá por un canal apropiado; luego, la otra persona decodificará el mensaje para comprenderlo. A su vez, esta persona receptora puede convertirse en un nuevo emisor. 
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema4/3.png', alt='Texto que describa la imagen')
          h4.text-center Proceso dinamizador
          p.mb-0 De esta manera, una vez que se participa en una relación comunicativa, esta estará actualizándose mediante el permanente intercambio de roles de emisor y receptor.
    separador


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
