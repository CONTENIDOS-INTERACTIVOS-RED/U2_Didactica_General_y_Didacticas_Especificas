<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'3. Didácticas específicas: edades de los alumnos'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-color-1.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.mb-3.mb-lg-0
          figure
            img(src='@/assets/curso/tema3/1.png', alt='')
        .col-lg
          .p-4
            p.mb-0(data-aos="fade-up") La didáctica específica se adapta a las etapas del desarrollo humano, considerando que las formas de aprender varían con la edad. Esta diferenciación permite diseñar estrategias pertinentes y efectivas para cada grupo (Camilloni, 2022).
    
    h2(data-aos="fade-left") Didáctica de niños
    p.mb-5 Se orienta al desarrollo integral: no solo se enseñan contenidos, sino que se favorece el crecimiento cognitivo, emocional, social y físico. El aprendizaje es activo y parte de la experiencia concreta del niño.

    .bg-full-width.bg-color-2.mb-5
      .p-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0 
                ul.lista-ul--color
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    P.mb-0 <b>El juego</b> es la herramienta central. A través de él se estimulan la creatividad, la resolución de problemas, el lenguaje, la motricidad y la interacción social.
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    P.mb-0 <b>La exploración del entorno</b> es clave para despertar la curiosidad y el pensamiento lógico.
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    P.mb-0 <b>La singularidad de cada niño</b> es respetada, adaptando las actividades a sus ritmos y estilos de aprendizaje (Bronfenbrenner & Morris, 2006).
              .col-lg-4(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema3/2.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/3.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") El docente cumple un rol fundamental como acompañante atento, que observa, escucha, documenta el proceso y ajusta su intervención según las necesidades individuales. Su tarea no se limita a enseñar, sino que crea un entorno seguro, estimulante y afectivo (Camilloni, 2022).
    
        .bg-color-3.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema3/4.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 El impacto de esta didáctica es profundo: al fomentar la autonomía, la confianza y la curiosidad, se sientan las bases para un aprendizaje continuo y significativo a lo largo de la vida.
    
    h2.mb-5(data-aos="fade-left")  Didáctica de adolescentes
    
    .bg-full-width.bg-color-5.mb-5
      .px-4.px-md-5
        .row.mb-5
          .col-lg-4.order-2
            figure
              img(src="@/assets/curso/tema3/5.png", data-aos="zoom-in")
          .col-lg-8.order-1.mb-3.mb-lg-0
            p.mb-4(data-aos="fade-left") La didáctica en esta etapa se enfoca en el desarrollo del pensamiento crítico, la autonomía y la construcción de identidad. Es una fase clave de transición hacia la adultez, donde los estudiantes buscan sentido y relevancia en lo que aprenden (Hmelo-Silver, 2004).
        
            .bg-color-2.p-4(data-aos="fade-left")
              ul.lista-ul--color
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  P.mb-0 Promueve el <b>aprendizaje significativo</b>, conectando los contenidos con los intereses, inquietudes y realidades del adolescente.
                li.d-flex
                  i.far.fa-arrow-alt-circle-right.bg-color-10
                  P.mb-0 Prioriza <b>metodologías activas</b> como:

        .row.justify-content-center.align-items-stretch.mb-4
          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema3/6.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Primero
                  p.mb-0 Aprendizaje basado en proyectos.

          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema3/7.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Segundo
                  p.mb-0 Estudio de casos.
          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema3/8.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Tercero
                  p.mb-0 Debates y simulaciones.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema3/9.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") Estas estrategias permiten reflexionar, argumentar y resolver problemas, desarrollando habilidades transferibles a la vida adulta.
    
        .bg-color-3.p-4(data-aos="fade-left")
          p.mb-0 El rol del docente se transforma en el de facilitador y guía, que acompaña el proceso de búsqueda personal. Se fomenta un entorno de confianza y respeto, donde los adolescentes puedan expresarse con libertad. Esta didáctica no solo busca logros académicos, sino también formar ciudadanos críticos, autónomos y socialmente responsables (Camilloni, 2022).
    
    p.mb-4 En este video, se presenta un recorrido por las diferentes formas de enseñanza dirigidas a jóvenes adultos, adultos en formación continua y personas mayores.

    .bg-full-width.bg-fondo-slider
      .p-4.p-md-5
        figure
          .video
            iframe(width="560" height="315" src="https://www.youtube.com/embed/CKAvtc52RRI?si=E48ScmmsjnYaEw-I" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
    
    .bg-full-width.bg-color-2
      .px-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-7.mb-3.mb-lg-0
            h2.mb-4(data-aos="flip-up") Didácticas específicas en función del contexto
            p.mb-4(data-aos="fade-right") Se invita a leer el documento “Didácticas específicas en función del contexto”, donde se aborda la importancia de adaptar la enseñanza a las características del entorno institucional, la disciplina académica y los estudiantes. 
    
            a.anexo.mb-4.bg-white.w-fit(:href="obtenerLink('/downloads/Anexo_1.pdf')" target="_blank")(data-aos="flip-up")
              .anexo__icono(:style="{'background-color': '#FCDFDB'}")
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p <strong>Anexo. </strong> Didácticas específicas en función del contexto.
    
          .col-lg-5
            figure(data-aos="zoom-in")
              img(src='@/assets/curso/tema3/10.png', alt='')

    .bg-full-width.border-top.actividad.bg-color-actividad
      .p-4.p-md-5
        #Actividad                
          <Actividad :cuestionario="cuestionario"/>

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://es.scribd.com/document/400845509/La-didactica-de-acuerdo-a-la-edad" target="_blank" rel="noopener noreferrer") La Didáctica de Acuerdo A La Edad. (2019). UNITEC. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://ojs.tdea.edu.co/index.php/senderos/article/download/961/1027/2104" target="_blank" rel="noopener noreferrer") Violante, R. (2018) Didáctica de la Educación Infantil. Reflexiones y Propuestas. Revista Senderos Pedagógicos • Nº9 • Enero - Diciembre 2018 • pp. 131 - 148.  
            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.campuseducacion.com/blog/revista-digital-docente/estrategias-didacticas-aula-educacion-primaria/" target="_blank" rel="noopener noreferrer") Lázaro Santana, F. A. (2018). Estrategias Didácticas en el aula de Educación Primaria. BLOG Noticias Oposiciones y Bolsas Trabajo Interinos. Campuseducacion.com. 

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=uuBw6oQIVQU" target="_blank" rel="noopener noreferrer") FILO UBA. (2020). Jugar y enseñar a jugar [video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')
  
</template>

<script>
import Actividad from '@/components/actividad/Actividad.vue'
export default {
  name: 'Tema3',
  components: {
    Actividad,
  },
  data() {
    return {
      cuestionario: {
        tema: 'Herramientas colaborativas para la construcción de paz',
        titulo: 'Ponte a prueba',
        introduccion:
          'Demuestra lo que aprendiste en esta unidad y pon a prueba tus conocimientos.',
        barajarPreguntas: true,
        preguntas: [
          {
            id: 1,
            texto:
              '1.	¿Cuál es el propósito central de las didácticas específicas dentro del proceso educativo?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Estandarizar los métodos de enseñanza para todas las disciplinas.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Eliminar las diferencias entre didáctica general y específica.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Adaptar las estrategias pedagógicas a las particularidades de disciplinas y contextos.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto: 'Limitar la inclusión de nuevos enfoques pedagógicos.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 2,
            texto:
              '¿Por qué es importante considerar los niveles del sistema educativo en las didácticas específicas?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'Para aplicar una metodología uniforme en todos los niveles.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Porque los recursos son iguales en todos los contextos.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Porque las características de los estudiantes varían, según las etapas de desarrollo.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'Para evitar diferencias en las estrategias pedagógicas.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 3,
            texto:
              '¿Qué rol cumplen las características de los sujetos en las didácticas específicas?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Influyen mínimamente en las estrategias de enseñanza.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Ayudan a diseñar estrategias inclusivas y equitativas.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto: 'Son irrelevantes para el diseño pedagógico.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto: 'Determinan un currículo rígido y estándar.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 4,
            texto:
              '¿Qué aspecto destaca la relación entre la didáctica general y las didácticas específicas?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto:
                  'La didáctica general es suficiente para cubrir todas las necesidades pedagógicas.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto:
                  'Ambas trabajan de manera complementaria en el proceso educativo.',
                esCorrecta: true,
              },
              {
                id: 'c',
                texto:
                  'Las didácticas específicas son independientes y no dependen de la general.',
                esCorrecta: false,
              },
              {
                id: 'd',
                texto:
                  'La didáctica general impone métodos a las didácticas específicas.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
          {
            id: 5,
            texto:
              '¿Cómo impacta la contextualización del tema en la enseñanza?',
            imagen: '',
            barajarRespuestas: true,
            opciones: [
              {
                id: 'a',
                texto: 'Reduce la diversidad de enfoques pedagógicos.',
                esCorrecta: false,
              },
              {
                id: 'b',
                texto: 'Evita que los estudiantes cuestionen los contenidos.',
                esCorrecta: false,
              },
              {
                id: 'c',
                texto:
                  'Sitúa los contenidos dentro de un marco relevante para el aprendizaje.',
                esCorrecta: true,
              },
              {
                id: 'd',
                texto:
                  'Restringe la adaptación a las necesidades de los estudiantes.',
                esCorrecta: false,
              },
            ],
            mensaje_correcto: '¡Muy bien! Ha acertado la respuesta.',
            mensaje_incorrecto: 'Lo sentimos, su respuesta no es la correcta.',
          },
        ],
        mensaje_final_aprobado:
          '¡Felicidades! Has superado la prueba con éxito.',
        mensaje_final_reprobado:
          'Te recomendamos repasar nuevamente la unidad para reforzar los conceptos clave antes de volver a intentarlo.',
      },
    }
  },
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass">
.bg-color-actividad
  background-color: #EBF1F5
</style>
