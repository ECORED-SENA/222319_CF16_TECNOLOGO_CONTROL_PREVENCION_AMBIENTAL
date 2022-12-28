<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 6
      h1 Responsabilidad social empresarial

    p.mb-4 Las organizaciones se ven cada vez más presionadas por los consumidores, los ciudadanos y las autoridades ambientales para que se comprometan a ofrecer productos y servicios con criterios de sostenibilidad e incluyan dentro de sus activos la protección ambiental, el cumplimiento de la normativa en temas relacionados con el respeto de los derechos laborales y humanos, la transparencia de la información y establezcan canales de comunicación directos y eficientes con las comunidades en las zonas donde desarrollan sus actividades.

    .row.justify-content-center.mb-4
      .col-lg-8
        .titulo-sexto.color-acento-contenido.mb-4
          h5.mb-0 Figura 3
          span Criterios de la RSE
        figure.mb-4
          img(src='@/assets/curso/tema6/fig1.svg', alt='Texto que describa la imagen')
        figcaption Nota. Adaptado de Escuela Nacional de Instructores (2016, p. 24).

    p.mb-4 Se debe tener en cuenta:

    SlyderF(columnas="col-lg-6 col-xl-4").mb-4
      .tarjeta-avatar
        img(src='@/assets/curso/tema6/avatar1.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h4.text-center Compromiso de toda la gestión
            p La responsabilidad social empresarial es el compromiso de las organizaciones, el cual toca toda su gestión y busca lograr positivos impactos en los diferentes sectores de la sociedad.

      .tarjeta-avatar
        img(src='@/assets/curso/tema6/avatar2.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h4.text-center Impactos múltiples
            p Este compromiso asumido permite gestionar de manera adecuada los impactos sociales, económicos y ecológicos con sus partes interesadas, el ambiente y la sociedad en su conjunto (Orjuela, 2020). 

      .tarjeta-avatar
        img(src='@/assets/curso/tema6/avatar3.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h4.text-center Normativa
            p A nivel nacional, el Instituto Colombiano de Normas Técnicas ICONTEC (2019) ha publicado la Norma GTC- ISO 26000; aunque esta norma no es certificable, sí orienta a cualquier tipo de organización que de manera voluntaria quiera implementar la RSE.

      .tarjeta-avatar
        img(src='@/assets/curso/tema6/avatar4.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h4.text-center Involucrando partes interesadas
            p Con la implementación de la RSE, se establecen las características, principios, prácticas, asuntos que se deben incluir, así como las condiciones para promocionar y desarrollar la política que exprese un compromiso responsable y que, también, involucre las partes interesadas bajo su influencia y permita establecer una adecuada comunicación en todos los niveles. 



</template>

<script>
export default {
  name: 'Tema6',
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
