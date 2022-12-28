<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 9
      h1 Instrumentos de evaluación

    p.mb-4 Para realizar un adecuado diagnóstico, seguimiento y medición de la eficacia y efectividad de las actividades inherentes a las labores que se realizan en un proceso de promotoría, como, por ejemplo, en una campaña de reciclaje, el promotor debe hacer uso de la evaluación.

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema9/img1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La evaluación es una parte fundamental en el proceso y una herramienta muy valiosa para el buen funcionamiento del programa, para lo cual, lo más adecuado es una evaluación continuada. Dentro de los instrumentos más comunes, se tienen: las listas de verificación, las encuestas y las evaluaciones a través de los cuestionarios de conocimiento. 
    separador 

    #t_9_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 9.1 Listas de verificación

    .row.align-items-center.mb-4
      .col-lg-6
        p.mb-4 Son documentos que se elaboran como una planilla o cuestionario, son una ayuda para el evaluador y permiten realizar, de manera ordenada y secuencial, las observaciones durante el desarrollo de una inspección, tarea, proceso.
        ul.lista-ul--color
          li 
            i.fas.fa-check
            p.mb-0 Es importante definir el método más pertinente para la adecuada recolección de información.
          li 
            i.fas.fa-check
            p.mb-0 Quien diligencie la lista de verificación debe estar debidamente capacitado en su uso. 
          li 
            i.fas.fa-check
            p.mb-0 Las listas de verificación deben ser entendibles, fáciles de diligenciar, sencillas, objetivas.
          li 
            i.fas.fa-check
            p.mb-0 Las listas de verificación han de centrarse en los aspectos claves de los requisitos a evaluar (Organización Panamericana de la Salud, 2020) 
      .col-lg-6
        figure
          img(src='@/assets/curso/tema9/1.png', alt='Texto que describa la imagen')
    separador 

    #t_9_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 9.2 Encuestas
    
    p.mb-4 Permiten obtener información relacionada con un tema, problema o situación. Para su diseño, se necesita saber su finalidad, qué se pretende con su utilización, determinar la población y la muestra, definir los recursos que se necesitarán, establecer la duración, forma de aplicación (muestral y poblacional), realizar un piloto y prever el modelo de cómo se va a procesar la información. Se utilizan instrumentos como los cuestionarios orales o escritos y pueden ser realizadas por medio de correo electrónico, llamada o de manera personal, entre otros. 

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema9/img2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Dentro de las ventajas que trae consigo la encuesta, es que la información recolectada puede ser crucial para empezar acciones de mejora o establecer las condiciones de ciertos temas, de acuerdo con la finalidad de la encuesta y la importancia que brinda. Como desventaja, se tiene el hecho de que la información recolectada no sea veraz o no haya sido contestada con responsabilidad y honestidad (Ariza, 2014).
    separador 

    #t_9_3.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 9.3 Listas de chequeo

    p.mb-4 Este instrumento de evaluación, muy flexible y adaptable a diferentes contextos, se conforma por una serie de ítems o variables a evaluar. Tales ítems son listados, los cuales el evaluador va a marcar de acuerdo con los criterios de evaluación establecidos. Por lo general, se valoran de manera positiva o negativa y si se manifiestan o no en el momento o a partir de la observación.

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema9/img3.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 A través de una lista de chequeo, se pueden evaluar aprendizajes, conductas, atributos, destrezas, acciones o procedimientos. Actividades que se pueden evaluar con este instrumento: desempeño en una tarea concreta (técnica, artística o científica), productos desarrollados en el campo, un laboratorio, un taller, entre otras. Se recomienda su uso para evaluación cualitativa, ya que permite obtener el nivel de logro, sea individual o grupal.
    separador

    #t_9_4.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 9.4	Evaluación para promotorías y capacitaciones

    p.mb-4 Para hacer un adecuado cierre de las actividades desarrolladas en la promotoría ambiental, se requiere realizar una evaluación integral, que contemple no solo la adquisición de conocimientos, a través de la aplicación de los cuestionarios, encuestas de satisfacción o informes de capacitación, sino que debe incluir todos los elementos que se desarrollaron o hicieron falta incluir dentro del proceso. También debe incluir la participación de los beneficiarios, teniendo presente:

    AcordionA(tipo="a" clase-tarjeta="tarjeta color-3")
      .row(titulo="Aspectos que debe cubrir")
        .col-md-3
          figure
            img(src='@/assets/curso/tema9/acor1.png', alt='Texto que describa la imagen')
        .col-md-9
          p Dentro de los aspectos que puede cubrir una evaluación, se tienen, por ejemplo, el cumplimiento de los objetivos, metas y actividades, a través del uso de sistema de indicadores. El grado de participación asociada a la asistencia, cualificación, número de actores e instituciones involucrados, acuerdos y pactos firmados, compromisos establecidos, agendas concertadas, planes y productos obtenidos y derivados.
        
      .row(titulo="Conocimientos, competencias y habilidades")
        .col-md-3
          figure
            img(src='@/assets/curso/tema9/acor2.png', alt='Texto que describa la imagen')
        .col-md-9
          p También, la evaluación ha de incluir registro del nivel de conocimiento adquirido, de la adquisición de competencias, habilidades y destrezas desarrolladas, de la efectividad en el uso medios de comunicación y capacitación de empleados, y, desde luego, el impacto en el desarrollo de la cultura ambiental en los individuos, la organización y la sociedad.

      .row(titulo="Cultura ambiental")
        .col-md-3
          figure
            img(src='@/assets/curso/tema9/acor3.png', alt='Texto que describa la imagen')
        .col-md-9
          p En los procesos de promotoría ambiental, interesa, de manera relevante, medir el nivel de cultura ambiental a partir de los valores relacionados con la temática ambiental ejecutada, como la protección del medio ambiente, la prevención de la contaminación, el respeto a la tierra. Igualmente, es posible incluir dentro de la evaluación el análisis frente a las creencias, como variables que anteceden y predicen actitudes y comportamientos en pro del medio ambiente. 
        
      .row(titulo="Actitudes ambientales adquiridas o potenciadas")
        .col-md-3
          figure
            img(src='@/assets/curso/tema9/acor4.png', alt='Texto que describa la imagen')
        .col-md-9
          p Otro elemento para incluir en la evaluación son las actitudes ambientales, ya que tienen una gran influencia sobre el comportamiento cuando otros factores no impiden que este se lleve a cabo, sobre todo en lo referente a los comportamientos individuales de consumo y de participación ambiental. Y finalmente, incluir las conductas proambientales, como grado de conocimiento de las causas y efectos de la problemática ambiental, motivación, capacidad de generar cambios y el grado de convencimiento de que su acción tendrá efectividad (Miranda, 2013). 

      .row(titulo="Mejora continua")
        .col-md-3
          figure
            img(src='@/assets/curso/tema9/acor5.png', alt='Texto que describa la imagen')
        .col-md-9
          p Finalmente, es importante ver la evaluación como parte del proceso permanente de mejora continua; como una actividad recurrente para mejorar el desempeño y no como un medio coercitivo (Organización Internacional de Normalización). De allí que esta sirva en todas las etapas para identificar las oportunidades de mejora y poder establecer las acciones preventivas y correctivas que de ella se deriven, permitiendo aprender de los problemas y actuar para que no se vuelvan a presentar (González, 2005). 

          .row(titulo="Mejora continua")
        .col-md-3
          figure
            img(src='@/assets/curso/tema9/acor5.png', alt='Texto que describa la imagen')
        .col-md-9
          p Finalmente, es importante ver la evaluación como parte del proceso permanente de mejora continua; como una actividad recurrente para mejorar el desempeño y no como un medio coercitivo (Organización Internacional de Normalización). De allí que esta sirva en todas las etapas para identificar las oportunidades de mejora y poder establecer las acciones preventivas y correctivas que de ella se deriven, permitiendo aprender de los problemas y actuar para que no se vuelvan a presentar (González, 2005). 

      .row(titulo="Fortalecimiento de las áreas del proceso")
        .col-md-3
          figure
            img(src='@/assets/curso/tema9/acor6.png', alt='Texto que describa la imagen')
        .col-md-9
          p Entonces, se deben identificar las áreas con problemas, las disposiciones para mitigar impactos, definir las responsabilidades para investigar y actuar, así como la metodología para identificar la causalidad y la solución de problemas identificados (Toro, 2017). 


</template>

<script>
export default {
  name: 'Tema9',
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
