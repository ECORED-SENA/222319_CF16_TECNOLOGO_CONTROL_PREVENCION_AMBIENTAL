<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 5
      h1 Tipos de pruebas en procesos de enseñanza-aprendizaje

    p.mb-4 Dentro de las herramientas más comunes para evaluar el proceso de enseñanza-aprendizaje, están las diferentes pruebas: orales, escritas, prácticas, evaluación con base en normas, evaluación con base en criterios, estandarizada, construida por el profesor, individual, grupal, aprovechamiento académico, de personalidad, de aptitudes, de inteligencia, de ubicación, de competencias, de dominio lingüístico, de actitudes y valores, objetiva, subjetiva, parcial, final y batería de pruebas.

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema5/img1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 En el proceso de una campaña ambiental, es fundamental identificar las generalidades de las pruebas de percepción, las pruebas de conocimiento, las pruebas de desempeño y el uso de indicadores.
    separador 

    #t_5_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 5.1	Pruebas de percepción

    p.mb-4 Esta herramienta se puede emplear antes, durante o al final del proceso educativo. Permite captar las percepciones en un momento dado; es decir, nos muestra la fotografía de cómo se percibe desde la mirada del individuo que expresa sus expectativas, valores, creencias, dominios y saberes. 

    SlyderF(columnas="col-lg-6 col-xl-4").mb-4
      .tarjeta-avatar
        img(src='@/assets/curso/tema5/avatar1.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center ¿Para qué sirven?
            p Sirven de insumo para identificar las necesidades del grupo.

      .tarjeta-avatar
        img(src='@/assets/curso/tema5/avatar2.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center ¿Qué ajustan?
            p Ajustan el proceso o acción de toma de decisiones y aplicación de acciones de mejora, para futuras intervenciones con relación a los vacíos y fortalezas en lo referente a información, capacitación, formación y toma de conciencia.

      .tarjeta-avatar
        img(src='@/assets/curso/tema5/avatar3.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center ¿Qué permiten detectar?
            p Permiten detectar las brechas y, así, poder establecer las estrategias pedagógicas pertinentes que le den respuesta a los desafíos en cuanto a lo procedimental y actitudinal. 

      .tarjeta-avatar
        img(src='@/assets/curso/tema5/avatar4.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center ¿Qué aseguran?
            p Como su propósito es detectar las desviaciones a tiempo, aseguran establecer, de manera temprana, las acciones correctivas que permitan ajustar y encauzar el proceso de manera eficaz. 

      .tarjeta-avatar
        img(src='@/assets/curso/tema5/avatar5.svg' alt='AvatarTop')
        .tarjeta.colorava
          .p-4
            h2.text-center ¿En qué más radica su importancia?
            p Son un insumo valioso para la planeación pedagógica; permiten orientar, seleccionar contenidos, metodologías, técnicas y materiales didácticos, entre otros, de conformidad con los resultados de aprendizaje y con la población objetivo.
    separador 

    #t_5_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 5.2	Pruebas de conocimiento   

    p.mb-4 Las pruebas de conocimiento miden el nivel de comprensión de los fundamentos y marcos teóricos; evalúan procesos y hechos, formas de usar el conocimiento frente a una situación o problema; responden a las preguntas ¿qué tiene que hacer?, ¿qué debe hacer? y ¿cómo se debe hacer? 

    .tarjeta.color-1.p-4.mb-4
      .row.align-items-center
        .col-lg-1
          figure.mb-2
            img(src='@/assets/curso/tema5/icon2.svg', alt='Texto que describa la imagen')
        .col-lg-11
          p.mb-0 Las pruebas de conocimiento se recolectan a través de evidencias de conocimiento y, habitualmente, el instrumento se diseña de acuerdo con los criterios preestablecidos de conformidad con los “Indicadores concretos de aprendizaje o parámetros; los cuales son utilizados para designar una base de referencia para el juicio de valor que se establece al evaluar” (Politécnico de Colombia, s. f., p. 13).
    separador

    #t_5_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 5.3	Pruebas de conocimiento   

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema5/img2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Las denominadas pruebas de desempeño de grupos sociales miden las destrezas, actitudes, apropiación cognitiva y evalúan cómo se desarrolla una actividad o proceso dentro de un contexto. Tales pruebas son fundamentales en el proceso de la campaña ambiental y se convierten en una herramienta garante del buen funcionamiento del programa de trabajo.
    
    .tarjeta.color-1.p-4.mb-4
      .row.align-items-center
        .col-lg-1
          figure.mb-2
            img(src='@/assets/curso/tema5/icon.svg', alt='Texto que describa la imagen')
        .col-lg-11
          p.mb-0 En la ejecución, las personas deben demostrar habilidades para aplicar el conocimiento, para el trabajo con otras personas, para la planeación, para sortear situaciones y problemas inherentes de la competencia que se quiere evaluar (Politécnico de Colombia, s. f., p. 12).
    separador 

    #t_5_4.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 5.4	Indicadores

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema5/img3.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 A partir de la línea base o situación inicial identificada en el diagnóstico participativo, se deben seleccionar las variables que se van a medir para determinar el avance o retroceso del proceso a desarrollar. Es decir, las características y condiciones que se quiere evaluar, ya sea en un ecosistema, sobre las concepciones, conocimientos o grado de participación de las personas, las actividades propuestas, los productos que se desean obtener, el desempeño, la gestión o el impacto. Se debe tener en cuenta:

    .tarjeta.colorsly.p-4.mb-5
      SlyderA(tipo="b")
        .row
          .col-lg-4
            h4 Comparar, monitorear y ajustar
            p Los indicadores son las señales o el termómetro que permiten medir el pulso en un momento particular, ya que, a través de ellos, es posible comparar, monitorear la trayectoria y ajustar, para garantizar el cumplimiento de los objetivos, metas y actividades propuestas en la planeación. 
        
          .col-lg-8
            figure.mb-2
              img(src='@/assets/curso/tema5/1.png', alt='Texto que describa la imagen')
              
        .row
          .col-lg-4
            h4 Huella ecológica
            p Un ejemplo es la huella ecológica, la cual permite analizar, por país, cuál es la demanda y oferta de los recursos naturales, ya que esto permite planificar el uso y manejo del territorio de manera adecuada. Esta mide las transformaciones que los seres humanos realizan en la naturaleza. Es por este motivo que se ha desarrollado un indicador a nivel global que mide el impacto de las actividades desarrolladas. Se define como el área biológicamente productiva que se requiere para suministrar los recursos usados por la población y para absorber sus residuos, y se confronta con la biocapacidad, es decir, <b>el área biológicamente productiva disponible per cápita</b> (WWF, 2017).
        
          .col-lg-8
            figure.mb-2
              img(src='@/assets/curso/tema5/2.png', alt='Texto que describa la imagen')
        
        .row
          .col-lg-4
            h4 Indicadores integrados
            p Dicho lo anterior, los indicadores no deben verse como elementos aislados, sino que, por el contrario, deben estar integrados dentro de un sistema de indicadores de diferente tipología, como son los cuantitativos o los cualitativos, estos deben tener un enfoque territorial, de inclusión y de derechos, donde se puedan medir las transformaciones sostenibles de los beneficiarios y el respeto de los modos de vida, dignidad y protección ambiental. 
        
          .col-lg-8
            figure.mb-2
              img(src='@/assets/curso/tema5/3.png', alt='Texto que describa la imagen')

        .row
          .col-lg-4
            h4 Indicadores y enfoques
            p Los indicadores podrían incluir el enfoque de los objetivos de desarrollo sostenible, la responsabilidad ambiental empresarial y social, garantizar los derechos humanos y el ejercicio de participación efectiva de los beneficiarios o afectados por el desarrollo del proceso (Wilches-Chaux, 2006).
        
          .col-lg-8
            figure.mb-2
              img(src='@/assets/curso/tema5/4.png', alt='Texto que describa la imagen')
        
        .row
          .col-lg-4
            h4 Indicadores comparables
            p Los indicadores deben ser comparables, orientados al cumplimiento de metas y objetivos, tener una visión equilibrada del proceso, ser evaluados de manera continua, periódica y deben ser claros y comprensibles para quien los emplee. (IHOBE, 1999. p. 13).
        
          .col-lg-8
            figure.mb-2
              img(src='@/assets/curso/tema5/5.png', alt='Texto que describa la imagen')
     
    .row.justify-content-center.mb-4
      .col-lg-10
        .titulo-sexto.color-acento-contenido.mb-4
          h5.mb-0 Figura 2
          span  Método para establecer indicadores medio ambientales
        figure.mb-4
          img(src='@/assets/curso/tema5/fig1.svg', alt='Texto que describa la imagen')
        figcaption Nota. Tomada de IHOBE (1999, p. 11).

    .row.justify-content-center.mb-4 
      .col-lg-8
        .tarjeta.colordegra.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/curso/tema5/www.png")
            .col
              .row.justify-content-between.align-items-center
                .col-lg-12.mb-sm-0.text-white
                  h4.mb-1 En las siguientes páginas, conozca sobre algunas instituciones y el manejo de indicadores, en relación con políticas públicas ambientales y la gestión ambiental:
                .col-lg-9.mb-sm-0.text-white
                  p  Sistema de Información Ambiental de Colombia del Instituto de Estudios Ambientales y Meteorológico (IDEAM, 2020).
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
                .col-lg-9.mb-sm-0.text-white
                  p  Sistema de Información Biológica del Instituto de investigaciones Biológicas Alexander von Humboldt (IAvH, 2020). 
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
                .col-lg-9.mb-sm-0.text-white
                  p  Observatorio Ambiental de Bogotá de la Secretaria Distrital de Ambiente (SDA, 2020).
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 
                .col-lg-9.mb-sm-0.text-white
                  p Índice de la Calidad del Aire (ICA) de (Aqicn, 2020).
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download 




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
