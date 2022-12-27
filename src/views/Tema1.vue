<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 1
      h1 La campaña ambiental

    p.mb-4 La campaña ambiental se convierte en la estrategia pedagógica que impacta en una población o comunidad objeto de aprendizaje. Cuando de estrategias para la promoción y la capacitación ambiental se trata, las campañas son herramientas inclusivas efectivas e impactantes por su relevancia en la comunidad. 

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img1.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 Según el Servicio de Asistencia Técnica para Bibliotecas Populares (2020), “las campañas pretenden mostrar con un mensaje gráfico y original las ventajas que implica una determinada actuación diferente a la habitual; la creatividad y el diseño se adaptan para clarificar las ideas a transmitir. Se dan razones para el cambio de actitud, se argumentan y fundamentan las ideas a partir de ejemplos sencillos. Se evoluciona de "querer hacer las cosas" a "hacer las cosas"”. (p. 6).

    .row.align-items-center.mb-4
      .col-lg-5
        p.mb-4 Por lo anterior, se debe prestar atención especial a:
        ul.lista-ul--color
          li 
            i.fas.fa-check
            p.mb-0 La problemática por tratar.
          li 
            i.fas.fa-check
            p.mb-0 Diseño de campaña y del material gráfico a difundir.
          li 
            i.fas.fa-check
            p.mb-0 Formación de educadores ambientales.
          li 
            i.fas.fa-check
            p.mb-0 Difusión y explicación puerta a puerta.
          li 
            i.fas.fa-check
            p.mb-0 Campañas municipales de nuevos elementos de gestión ambiental.
          li 
            i.fas.fa-check
            p.mb-0 Campañas de publicidad y marketing ambiental.
          li 
            i.fas.fa-check
            p.mb-0 Campañas específicas.
      .col-lg-7
        figure
          img(src='@/assets/curso/tema1/1.png', alt='Texto que describa la imagen')
    
    .row.justify-content-center.mb-4 
      .col-lg-8
        .tarjeta.colordegra.p-3.mb-5
          .row.justify-content-around.align-items-center
            .col-3.col-sm-2.col-lg-2
              img(src="@/assets/curso/tema1/you.png")
            .col
              .row.justify-content-between.align-items-center
                .col.mb-3.mb-sm-0.text-white
                  h4.mb-1 TheEcoFace. (2012). Responsabilidad Ambiental [Video]. YouTube. 
                  p  Para contextualizar el concepto anterior, se le invita a ingresar al siguiente enlace. Tome nota atenta de los aspectos más importantes que encuentre en el video:
                .col-sm-auto
                  a.boton.colorboton(:href="obtenerLink('downloads/tabla1.pdf')" target="_blank")
                    span Descargar
                    i.fas.fa-file-download
    separador

    #t_1_1.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 1.1	Características de la campaña ambiental

    p.mb-4 Cuando se realizan las campañas de comunicación ambiental, estas deben tener objetivos acertados para que su mensaje y sus ideas lleguen de manera eficaz, y así los resultados del proyecto tengan un impacto positivo en el entorno que se afecta.

    .titulo-sexto.color-acento-contenido.mb-4
      h5.mb-0 Figura 1
      span Características de la campaña
    .row.justify-content-center.mb-4
      .col-lg-6
        figure
          img(src='@/assets/curso/tema1/fig1.svg', alt='Texto que describa la imagen')

    .tarjeta.color-1.p-4
      .row.align-items-center
        .col-lg-1
          figure.mb-2
            img(src='@/assets/curso/tema1/icon.svg', alt='Texto que describa la imagen')
        .col-lg-11
          p.mb-0 Para que una campaña ambiental tenga un propósito más holístico sobre el medio ambiente que se afecta, es importante que la campaña genere en los receptores del mensaje, un cambio de conducta, actitud y, sobre todo, se cree una conciencia más allá del concepto de hacer las cosas bien: entender que cada acción conlleva una consecuencia, que afecta a toda la sociedad directamente.
    separador

    #t_1_2.titulo-segundo.color-acento-contenido(data-aos="fade")
      .h2 1.2	Pasos para el diseño de una campaña ambiental

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img2.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 El diseño de una campaña ambiental es un aspecto muy importante para el logro de la educación ambiental en una comunidad o sector a trabajar; por ende, se establecen una serie de pasos a tener en cuenta para la realización de un proyecto. Según el Servicio de Asistencia Técnica para Bibliotecas Populares (2020, p.1), los siguientes son los elementos a tener en cuenta:

    .row.justify-content-center.mb-4
      .col-lg-8
        .row.align-items-center
          .col-lg-4
            ul.lista-ul--color
              li 
                i.fas.fa-check
                p.mb-0 Diagnóstico
              li 
                i.fas.fa-check
                p.mb-0 Identificación de la población
              li 
                i.fas.fa-check
                p.mb-0 Plantear objetivos
              li 
                i.fas.fa-check
                p.mb-0 Definir estrategias
              li 
                i.fas.fa-check
                p.mb-0 Difundir mensajes
              li 
                i.fas.fa-check
                p.mb-0 Realizar la campaña
              li 
                i.fas.fa-check
                p.mb-0 Evaluar la campaña
          .col-lg-8
            figure.mb-2
              img(src='@/assets/curso/tema1/2.png', alt='Texto que describa la imagen')
    
    .row.mb-4 
      .col-lg-2
        .row 
          .col-10
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 Diagnóstico

    p.mb-4 En el primer paso, el diagnóstico, se debe determinar la temática para trabajar en la campaña de concientización. Algunas temáticas recurrentes por su pertinencia pueden ser medio ambiente, trabajo y productividad, violencias diversas, derechos del consumidor, derechos del niño/a, derechos de las mujeres, discriminación, identidad, cultura y sociedad, enfoques diferenciales para las acciones comunitarias, contribuyentes, entre otras. 

    .tarjeta.color-1.p-4.mb-4
      .row.align-items-center
        .col-lg-1
          figure.mb-2
            img(src='@/assets/curso/tema1/icon2.svg', alt='Texto que describa la imagen')
        .col-lg-11
          p.mb-0 Tal determinación de la temática debe responder a la demanda de la comunidad, a sus verdaderas y actuales necesidades de crecimiento, desarrollo, transformación, mejora de condiciones. Es así como la definición del tema de campaña puede contar, de manera directa, con aportes de los agentes comunitarios donde se llevará a cabo el proceso. 

    .row.mb-4 
      .col-lg-3
        .row 
          .col-12
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 Identificación de la población

    .bloque-texto-g.color-primario.p-4.p-sm-4.p-md-5.mb-4
      .bloque-texto-g__img(
        :style="{'background-image': `url(${require('@/assets/curso/tema1/img3.jpg')})`}"
      )
      .bloque-texto-g__texto.p-5
        p.mb-0 La identificación de la población con la que ha de llevarse a cabo el proceso de campaña ambiental es trascendental, debido a que las estrategias y métodos para llegar a ella cambian sustancialmente dependiendo de factores como los sociales, culturales, políticos, geográficos, económicos, etc. El Servicio de Asistencia Técnica para Bibliotecas Populares (2020, p.1) sugiere algunas actividades para realizar tal identificación:

    .row.align-items-center.mb-4
      .col-lg-5
        ul.lista-ul--color
          li 
            i.fas.fa-check
            p.mb-0 “Colocar urnas en la biblioteca y en lugares públicos (comercios de la zona, escuelas, clubes del barrio, etc.) para que los ciudadanos coloquen en un papel la problemática ante la cual la comunidad debe tomar conciencia para lograr cambios respecto de la situación actual (contaminación ambiental, desigualdad de oportunidades, violencia, problemáticas referidas a la salud, entre otras).
          li 
            i.fas.fa-check
            p.mb-0 Realizar encuestas a miembros de la comunidad, delimitando un radio a relevar, para detectar las temáticas de interés local.
          li 
            i.fas.fa-check
            p.mb-0 Registrar, en un periodo determinado, las consultas realizadas por los usuarios en el Servicio de Información Ciudadana para localizar las más frecuentes.”
      .col-lg-7
        figure
          img(src='@/assets/curso/tema1/3.png', alt='Texto que describa la imagen')

    .row.mb-4 
      .col-lg-4
        .row 
          .col-12
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 Plantear objetivos y definir estrategias

    p.mb-4 Teniendo en cuenta la temática y las necesidades detectadas en el diagnóstico, hay que ver qué es lo que se quiere lograr y, entonces, establecer los plazos que se le van a conceder al proyecto. Los objetivos deben entenderse como orientaciones que conducirán el proceso de la campaña ambiental. Hacia esas orientaciones habría que encaminar, desde luego, cada acción, estrategia, plazo, participantes, en definitiva, la marcha misma de la campaña.

    .tarjeta.color-1.p-4.mb-4
      .row.align-items-center
        .col-lg-1
          figure.mb-2
            img(src='@/assets/curso/tema1/icon3.svg', alt='Texto que describa la imagen')
        .col-lg-11
          p.mb-0 En cuanto a la definición de las estrategias y según el Servicio de Asistencia Técnica para Bibliotecas Populares, las actividades sugeridas deben girar en torno a la realización de “eventos culturales, teatro, muestras artísticas, cine debate, jornadas lúdicas, conferencias, etc., con el fin de que el contacto físico sea una estrategia que refuerce la concientización (si la temática lo permite, por ejemplo, en caso de que se realice una Campaña contra la discriminación, pueden montarse obras de teatro referidas a esa problemática)” (p. 1).

    .row.mb-4 
      .col-lg-2
        .row 
          .col-12
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 Difundir mensajes

    p.mb-4 La difusión de la campaña implica acciones organizadas y articuladas de transferencia de información, mediante mecanismos justos, apropiados y cercanos para todos aquellos individuos o colectivos a quienes se pretenda involucrar y/o impactar. Según el Servicio de Asistencia Técnica para Bibliotecas Populares, las siguientes son las actividades sugeridas:

    .row.align-items-center.mb-4
      .col-lg-6
        ul.lista-ul--color
          li 
            i.fas.fa-check
            p.mb-0 Contactarse con organismos y/o instituciones referidas a la temática de la campaña para recabar información que sirva de insumo para producir los mensajes. 
          li 
            i.fas.fa-check
            p.mb-0 Conectarse con especialistas en la temática para pedir colaboración en el aporte de contenidos que servirán para formular los mensajes. 
          li 
            i.fas.fa-check
            p.mb-0 Llevar la propuesta a las escuelas y trabajar en conjunto con los estudiantes en la producción de folletería, afiches, boletines informativos.
          li 
            i.fas.fa-check
            p.mb-0 Contactarse con radios y otros medios locales para pedir colaboración u orientación en el armado de piezas radiales y/o audiovisuales. 
          li 
            i.fas.fa-check
            p.mb-0 Articular con universidades, escuelas o talleres de periodismo para pedir colaboración u orientación en la producción de contenidos. (p. 2)
      .col-lg-6
        figure
          img(src='@/assets/curso/tema1/4.png', alt='Texto que describa la imagen')

    .row.mb-4 
      .col-lg-4
        .row 
          .col-12
            .tarjeta.color-secundario.p-2
              h4.text-center.mb-0 Realizar la campaña y evaluar la campaña
    p.mb-4 Una vez ya se han ejecutado los pasos anteriores, es momento de poner en marcha la campaña misma, sin perder de vista, en ningún sentido, algunas variables como el tiempo, el sitio, los materiales, el personal, la seguridad, las didácticas y metodologías, las condiciones del entorno, los objetivos, los resultados esperados, entre otras que merezcan consideración para la efectividad del proceso.
    p.mb-4 Finalizada la campaña, e incluso dentro de su mismo desarrollo, evaluar el proceso amerita:

    .row.mb-4
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema1/5.png', alt='Texto que describa la imagen')
          h4.text-center Chequeo y verificación
          p.mb-0 Revisar lo realizado y el impacto de la campaña en función de los recursos destinados a la misma (humanos, económicos, materiales).
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema1/6.png', alt='Texto que describa la imagen')
          h4.text-center Consultar y analizar percepciones
          p.mb-0 Hacer encuestas a la población destinataria de los mensajes con preguntas claves para determinar el grado de toma de conciencia con respecto a la problemática que se trabajó.
      .col-lg-4
        .tarjeta.color-2.p-4
          figure.mb-2 
            img(src='@/assets/curso/tema1/7.png', alt='Texto que describa la imagen')
          h4.text-center Responsabilizar personas y colectivos
          p.mb-0 Convocar a charlas o asambleas vecinales para intercambiar experiencias y opiniones acerca de las medidas que deben tomarse con respecto a la temática en cuestión.

</template>

<script>
import Muestras from '../components/Muestras' // borrar una vez el componente "Muestras" no se necesite
export default {
  name: 'Tema1',
  components: {
    Muestras, // borrar una vez el componente "Muestras" no se necesite
  },
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
