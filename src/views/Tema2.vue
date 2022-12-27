<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Comunicación asertiva en procesos de promotoría ambiental

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La comunicación se convierte en la herramienta más necesaria para realizar un proceso de educación ambiental; esta debe ser en doble vía y eminentemente asertiva para que la retroalimentación y el mensaje lleguen con efectividad. Para tener en cuenta cómo influye de manera importante la comunicación en los diversos procesos de promotoría ambiental, es necesario partir del concepto de comunicación. Según Gambini et al., (2018, p. 10), “la palabra deriva del latín communicare, que significa “compartir algo, poner en común””. 
    .row.mb-4
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema1/1.png', alt='Texto que describa la imagen')
          h4.text-center Proceso natural
          p.mb-0 Por lo tanto, la comunicación es un fenómeno inherente a la relación que los seres vivos mantienen cuando se encuentran en grupo.
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema1/2.png', alt='Texto que describa la imagen')
          h4.text-center Proceso dinámico
          p.mb-0 La comunicación es un proceso que se inicia en la intención de una persona, quien construirá un mensaje y lo transmitirá por un canal apropiado; luego, la otra persona decodificará el mensaje para comprenderlo. A su vez, esta persona receptora puede convertirse en un nuevo emisor. 
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema1/3.png', alt='Texto que describa la imagen')
          h4.text-center Proceso dinamizador
          p.mb-0 De esta manera, una vez que se participa en una relación comunicativa, esta estará actualizándose mediante el permanente intercambio de roles de emisor y receptor.
    separador

    #t_2_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.1	¿Qué y cómo nos comunicamos?

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Lo que comunicamos y cómo lo comunícanos, parte específicamente del proceso de transferencias de información, por ende, “en todo lo que hacemos, decimos o dejamos de hacer, estamos comunicando algo. En esta relación puede no haber palabras, por ejemplo, entre pasajeros de un medio de transporte, donde lo esperable es que no se converse entre extraños. Si no hablamos, igual estamos comunicando, ya sea con la posición de nuestro cuerpo, con nuestras miradas, la expresión facial, etc. En ese sentido, es importante siempre tener en cuenta que existen estas dos formas de comunicarnos: verbal y no verbal”. (Gambini et al., 2018, p. 10)

    .tarjeta.color-1.p-4.mb-4
      .row.align-items-center
        .col-lg-1
          figure.mb-2
            img(src='@/assets/curso/tema2/icon.svg', alt='Texto que describa la imagen')
        .col-lg-11
          p.mb-0 La comunicación verbal se refiere a la comunicación a través de la palabra, lo que decimos o escribimos, mientras que la comunicación no verbal corresponde a gestos, actitudes, posturas corporales, tono de voz o miradas.

    .row.justify-content-center.mb-4 
      .col-lg-8
        .tarjeta.colordegra.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/curso/tema1/you.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4.mb-1 Ortiz, W. (2017). Comunicación verbal y no verbal.
                  p  Para afianzar en este punto, visite el enlace del video que aquí se propone. Preste mucha atención a los elementos teóricos y prácticos que en él se muestran.
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    separador 

    #t_2_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.2	Los elementos de la comunicación

    p.mb-4 Cuando hay comunicación, se establece una relación entre dos fuentes. Según Gambini et al. (2018, p. 16), “La comunicación consiste en la emisión y recepción de mensajes entre dos o más personas o animales. Quienes se comunican buscan aportar y obtener información acerca de un determinado asunto. Se conoce como proceso comunicativo, por lo tanto, al conjunto de actividades vinculadas a este intercambio de datos. Dicho proceso requiere de, al menos, un emisor y de un receptor”. Es por esto que los elementos del proceso de comunicación requieren de, por lo menos, los siguientes actores en el proceso de intercambio de información: 

    AcordionA(tipo="a" clase-tarjeta="tarjeta color-3")
      .row(titulo="El emisor (codificador)")
        .col-md-3
          figure
            img(src='@/assets/curso/tema2/acor1.png', alt='Texto que describa la imagen')
        .col-md-9
          p Es la persona que emite o envía el mensaje. Cuando la persona que idea y crea el mensaje es la misma que lo transmite, fuente y emisor se consideran un solo elemento. (p. 16)
        
      .row(titulo="El receptor (decodificador)")
        .col-md-3
          figure
            img(src='@/assets/curso/tema2/acor2.png', alt='Texto que describa la imagen')
        .col-md-9
          p Es la persona o grupo de personas a quien o a quienes se dirige el mensaje. Es el destinatario o la audiencia objetivo de la comunicación y todo aquel que acepte el mensaje. (p. 16)

      .row(titulo="El código")
        .col-md-3
          figure
            img(src='@/assets/curso/tema2/acor3.png', alt='Texto que describa la imagen')
        .col-md-9
          p Es el sistema estructurado de signos, como son los lenguajes español, inglés, etc., u otros lenguajes como la música o la pintura.
        
      .row(titulo="El mensaje")
        .col-md-3
          figure
            img(src='@/assets/curso/tema2/acor4.png', alt='Texto que describa la imagen')
        .col-md-9
          p Es el contenido expresado y transmitido por el emisor al receptor, el cual tiene un contenido (ideas que constituyen el mensaje) y el tratamiento, que sería el modo de decir las cosas, lo cual facilita el entendimiento del mensaje.

      .row(titulo="El canal")
        .col-md-3
          figure
            img(src='@/assets/curso/tema2/acor5.png', alt='Texto que describa la imagen')
        .col-md-9
          p Es el medio o vehículo físico por el cual se envía y viaja el mensaje. Una carta, un cartel, el periódico, la computadora, las ondas sonoras y electromagnéticas, etc.
        
      .row(titulo="La retroalimentación")
        .col-md-3
          figure
            img(src='@/assets/curso/tema2/acor6.png', alt='Texto que describa la imagen')
        .col-md-9
          p Es el elemento clave que propicia la interacción o transacción entre el emisor y el receptor, ya que ambas partes se aseguran de que el mensaje fue recibido y compartido. También el mensaje mismo es fuente de retroalimentación; por ejemplo, cuando una persona está escribiendo y, después de leer el texto, corrige los errores.

      .row(titulo="El contexto")
        .col-md-3
          figure
            img(src='@/assets/curso/tema2/acor7.png', alt='Texto que describa la imagen')
        .col-md-9
          p Se refiere al ambiente físico, la situación social y el estado psicológico en que se encuentran emisor y receptor en el momento de la comunicación. (p. 17).
    separador    
     
    #t_2_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 2.3	Técnicas de expresión y comunicación oral

    p.mb-4 Cuando se trata de aplicar técnicas didácticas para capacitar a determinada población, existen diversos tipos de recursos. En cuanto a las técnicas de expresión y comunicación oral, muy aportantes en una campaña ambiental, se requiere considerar las más empleadas y aquellas que generan gran impacto en el proceso de capacitación, instrucción o educación ambiental. 

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img3.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Es mediante ellas como la población y personas del proceso asimilarán con mayor propiedad el mensaje, asumirán responsabilidades, comprenderán su implicación en el proceso ambiental y, sobre todo, se convertirán en potenciales transmisores del enfoque e intención de la campaña. 

    .row.mb-4 
      .col-lg-2
        .row 
          .col-10
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 La exposición

    p.mb-4 “Se puede decir que la exposición académica es aquella presentación oral que se realiza en un contexto académico (aula de la universidad, conferencia, etc.) con la principal intención de dar a conocer un tema específico siguiendo un orden (introducción, desarrollo y conclusión), utilizando un lenguaje formal” (Gambini et al., 2018, p. 88).

    .row.justify-content-center.mb-4
      .col-lg-10
        .row.align-items-center
          .col-lg-6
            p.mb-4 Las principales características de la exposición académica son: 
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-2 Cumple una función referencial (informa o explica un tema). 
              li 
                i.fas.fa-check
                p.mb-2 Uso del lenguaje objetivo y formal (estándar culto). 
              li 
                i.fas.fa-check
                p.mb-2 Presentación de las ideas de manera ordenada y progresiva. 
              li 
                i.fas.fa-check
                p.mb-2 Manejo de vocabulario científico y técnico referente al tema.
          .col-lg-6
            figure.mb-2
              img(src='@/assets/curso/tema2/4.png', alt='Texto que describa la imagen')

    .row.mb-4 
      .col-lg-2
        .row 
          .col-10
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 El debate

    .row.mb-4
      .col-lg-11
        .row
          .col-lg-6
            p.mb-4 Es importante tener en cuenta que otra técnica de expresión que permite integrar de forma objetiva una comunidad y conocer lo que piensan es el debate. <b>“El debate (del lat. debattuĕre 'discutir, disputar sobre algo')</b> es una técnica, tradicionalmente de comunicación oral, que consiste en la discusión de opiniones antagónicas sobre un tema o problema. En esta técnica, dos o más expertos conversan sobre un tema ante el grupo siguiendo un esquema previo”. (Gambini et al., 2018, p. 119).
          .col-lg-6
            figure.mb-2
              img(src='@/assets/curso/tema2/5.png', alt='Texto que describa la imagen')

    .tarjeta.color-1.p-4.mb-4
      .row.align-items-center
        .col-lg-1
          figure.mb-2
            img(src='@/assets/curso/tema2/icon2.svg', alt='Texto que describa la imagen')
        .col-lg-11
          p.mb-0 Dentro de las características más sobresalientes del debate, está la de ofrecer información y actualización de opiniones y puntos de vista significativos para el auditorio. También, el debate aumenta la fluidez del diálogo gracias a la reducción del número de expertos. Finalmente, el debate permite un repaso exhaustivo de las posturas de los especialistas.

    .row.mb-4 
      .col-lg-2
        .row 
          .col-12
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 La mesa redonda

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img4.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Una de las técnicas más empleadas para compartir ideas y debatirlas en pro de un objetivo común es la mesa redonda, y, según Gambini et al. (2018, p. 114), <b>“es una técnica donde se presentan diferentes puntos de vista, no necesariamente contradictorios, acerca de un tema determinado, ante un público y con la ayuda de un moderador”.</b>

    p.mb-4 La mesa redonda, entre otros, tiene como objetivos fundamentales:

    .row.justify-content-center.mb-4
      .col-lg-8
        .row 
          .col-lg-6
            .tarjeta.color-2.p-4
              figure.mb-2 
                img(src='@/assets/curso/tema2/6.png', alt='Texto que describa la imagen')
              p.mb-0 Fomentar el diálogo entre los participantes para desarrollar el tema desde diferentes áreas o puntos de vista.
          .col-lg-6
            .tarjeta.color-2.p-4
              figure.mb-2 
                img(src='@/assets/curso/tema2/7.png', alt='Texto que describa la imagen')
              p.mb-0 Facilitar el interés hacia determinadas cuestiones, motivando a la investigación o a la acción y búsqueda de soluciones.

    .row.mb-4 
      .col-lg-2
        .row 
          .col-8
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 El foro

    .row.mb-4
      .col-lg-12
        .row
          .col-lg-6
            p.mb-4 Se trata de una técnica en la cual varias personas discuten un tema determinado, ante un auditorio, bajo la conducción de un coordinador. Suele utilizarse como complemento de otras técnicas previas (panel, conferencia, etc.), dando lugar, en ocasiones, a otras técnicas específicas (cinefórum, discofórum, etc.). (Gambini et al., 2018, p. 115).
            p.mb-4 Mediante el foro, y más aún en el contexto de una campaña ambiental, es posible:
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-2 Desarrollar una deliberación sistemática sobre el tema previamente considerado. 
              li 
                i.fas.fa-check
                p.mb-2 Conocer genéricamente las opiniones y actitudes del grupo. 
              li 
                i.fas.fa-check
                p.mb-2 Fomentar la libre expresión con mínimas limitaciones. 
              li 
                i.fas.fa-check
                p.mb-2 Aumentar la transmisión de información.
          .col-lg-6
            figure.mb-2
              img(src='@/assets/curso/tema2/8.png', alt='Texto que describa la imagen')

    .row.mb-4 
      .col-lg-2
        .row 
          .col-10
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 El seminario

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema2/img2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 El seminario se constituye en la técnica que agrupa a mayor cantidad de personas, generalmente en un auditorio, pero puede ser cualquier espacio adaptado para acoger a todos los individuos convocados. El seminario permite difundir el mensaje de manera directa a los espectadores. Según Gambini et al. (2018, p. 116), el seminario es la <b>“Técnica grupal que tiene por objeto la investigación o estudio intensivo de un tema en reuniones de trabajo debidamente planificadas. Constituye un verdadero grupo de aprendizaje activo, pues los miembros indagan por sus propios medios”. Están:</b>

    .row.justify-content-center.mb-5
      .col-lg-11.position-relative
        .avatar
          figure
            img(src="@/assets/curso/tema2/vec1.svg", alt="alt").img250
        .crd.crd--avatarHorizontal.crd--first.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema2/avatar1.svg", alt="alt").img100
            .col
              h5 Pensamiento crítico
              .row
                .col-10
                  p Esta técnica del seminario busca promover el pensamiento crítico y reflexivo.
        .crd.crd--avatarHorizontal.colors.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema2/avatar2.svg", alt="alt").img100
            .col
              h5 Razonamiento y responsabilidad
              .row
                .col-10
                  p Mediante el seminario, es posible intensificar el razonamiento objetivo y la responsabilidad individual y colectiva del grupo, para trabajar en la investigación de los diferentes tópicos del tema.
        .crd.crd--avatarHorizontal.colors2.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema2/avatar3.svg", alt="alt").img100
            .col
              h5 26 de enero
              .row
                .col-10
                  p Según el portal www.comunidadism.es (2020), el día 26 de enero se celebra el «Día Mundial de la Educación Ambiental», que tiene su origen en 1975, año en que se celebró en Belgrado (capital de la República de Serbia), el Seminario Internacional de Educación Ambiental, donde participaron expertos de más de 70 países. 
        .crd.crd--avatarHorizontal.colors3.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema2/avatar2.svg", alt="alt").img100
            .col
              h5 Principios de la E.A.
              .row
                .col-10
                  p En este evento, se establecieron los principios de la Educación Ambiental en el marco de los programas de las Naciones Unidas. 
        .crd.crd--avatarHorizontal.crd--last.py-4
          .row.align-items-center
            .col-auto
              figure
                img(src="@/assets/curso/tema2/avatar3.svg", alt="alt").img100
            .col
              h5 Carta de Belgrado
              .row
                .col-10
                  p Como resultado, se publicó la Carta de Belgrado, en la cual se plasman las reivindicaciones fundamentales de la Educación Ambiental.



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
