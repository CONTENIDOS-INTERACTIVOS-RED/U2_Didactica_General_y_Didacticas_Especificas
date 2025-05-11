<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'1. Fundamentación conceptual y criterios de las didácticas específicas'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .bg-full-width.bg-color-5
      .p-4.p-md-5
        .row.mb-5
          .col-lg-4.order-2
            figure
              img(src="@/assets/curso/tema1/1.png", data-aos="zoom-in")
          .col-lg-8.order-1.mb-3.mb-lg-0
            .bg-color-4.p-4.mb-5(data-aos="fade-left")
              .row.align-items-start
                .col-lg-auto
                  img(src="@/assets/curso/tema1/2.svg", style="max-width: 90px").mx-auto
                .col-lg
                  p.mb-0 Para Martos (2022), la <em>didáctica</em> es un campo del conocimiento que ha dado lugar a diversas discusiones académicas. Algunos autores sostienen la existencia de una única didáctica, mientras que otros proponen diversas variantes, como la <em>didáctica general</em> y la <em>didáctica específica</em> (también llamada especial). Esta última se refiere a las prácticas educativas aplicadas a contextos particulares, aunque su conceptualización teórica moderna se remonta a John Franklin Bobbitt, quien en 1918, escribió un ensayo donde diferencia la didáctica general de la específica.
            p(data-aos="fade-left") El concepto de <em>didáctica específica</em> cuenta con distintos enfoques epistemológicos:
        
        .row.justify-content-center.align-items-stretch.mb-4
          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/3.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Primero
                  p.mb-0 Algunos la consideran una ciencia autónoma.

          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/4.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Segundo
                  p.mb-0 Otros, una derivación de la didáctica general.
          .col-lg-4.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/5.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Tercero
                  p.mb-0 Un tercer grupo, la entiende como una técnica.
    
    p.mb-4 Esta diversidad ha generado clasificaciones que incluyen la didáctica general, la didáctica especial o específica y la didáctica diferencial, lo que puede causar confusiones en su comprensión. Por ello, es necesario precisar sus definiciones para una mejor comprensión del campo didáctico.

    h2(data-aos="fade-left") Diferenciación entre tipos de didáctica
    p.mb-5 A continuación, se sintetizan sus principales características:

    .bg-full-width.bg-color-7
      .p-4.p-md-5
        TabsC.color-acento-contenido.mb-5
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Didáctica específica" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Didáctica específica
                p Aborda cómo enseñar contenidos propios de una disciplina determinada (como matemáticas, lengua, ciencias). Se enfoca en estrategias, metodologías y materiales ajustados a las características del saber que se enseña. Busca la eficacia en la transmisión del conocimiento disciplinar (Martos, 2022).
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema1/6.png', alt='')
        
          .tabs-content.border.px-4.p-md-5.py-3(titulo="Didáctica diferencial" :icon="require('@/assets/bullets/1.svg')")
            .row.justify-content-center.align-items-center
              .col-lg-7.col-xl-8.mb-4.mb-md-0.order-2
                h4 Didáctica diferencial
                p Centra su atención en las características particulares de los estudiantes o grupos (por ejemplo, adultos mayores, personas con discapacidad, niños en contextos vulnerables). Propone metodologías inclusivas, flexibles y adaptadas a la diversidad. Reconoce diferentes formas de percibir y aprender la realidad (Martos, 2022).
        
              .col-md-8.col-lg-5.col-xl-4.order-1.mb-3.mb-lg-0
                figure(data-aos="zoom-in")
                  img(src='@/assets/curso/tema1/7.png', alt='')
        
        h2(data-aos="fade-left") Aportes desde Cuesta, Calderaro y Bombini (2014)
        p.mb-5 Estos autores coinciden en que la didáctica específica se nutre de la didáctica general, pero se centra en la comunicación de saberes particulares dentro de un área del conocimiento. Para desarrollarla, es necesario atender no solo al contenido, sino también a las dinámicas del aula:

        .row.justify-content-center.align-items-stretch.mb-4
          .col-lg-3.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/8.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Primero
                  p.mb-0 Relaciones de poder

          .col-lg-3.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/9.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Segundo
                  p.mb-0 Construcción del conocimiento
          .col-lg-3.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/10.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Tercero
                  p.mb-0 Comunicación
          .col-lg-3.mb-3.mb-lg-0
            .bg-color-6.p-4(data-aos="fade-left").h-100
              .row.align-items-center
                .col-lg-auto
                  img(src="@/assets/curso/tema1/13.svg", style="max-width: 90px").mx-auto
                .col-lg
                  h5.mb-2 Tercero
                  p.mb-0 Contrato social
    
    p.mb-4 Asimismo, se requiere diseñar materiales adecuados, formular preguntas que estimulen el pensamiento crítico y reflexionar sobre las prácticas docentes. En este sentido, el aula se convierte en un verdadero laboratorio donde convergen la didáctica general y las específicas, para crear estrategias pedagógicas efectivas.

    .bg-full-width.bg-color-5
      .p-4.p-md-5
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0.order-lg-2
    
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/12.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Conexión con la práctica
                p.text-center Se construye a partir del análisis de situaciones reales en el aula.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/13.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Comunicación de saberes
                p.text-center Estudia cómo se enseñan y aprenden los contenidos propios de cada disciplina.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/14.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Materiales y estrategias
                p.text-center Implica el diseño de recursos y métodos acordes con la especificidad del área de conocimiento.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/15.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Reflexión docente
                p.text-center Promueve el análisis constante sobre la propia práctica de enseñanza.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema1/16.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Relación con la general
                p.text-center Aplica los principios de la didáctica general a contextos y contenidos particulares.
    
          .col-lg-4.order-lg-1
            figure
              img(src='@/assets/curso/tema1/11.png', alt='')
    
        h2(data-aos="fade-left") Enfoques complementarios y tensiones
        p Cuesta, Calderaro y Bombini (2014), insisten en que la didáctica específica responde a la necesidad de considerar las particularidades de cada disciplina, como matemáticas, ciencias o lengua. A diferencia de la general, que ofrece un marco teórico amplio, la específica permite analizar las prácticas de enseñanza desde el contenido disciplinar.
    
    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema1/17.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        .bg-color-3.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/18.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 No obstante, este enfoque especializado también implica riesgos: puede fragmentar la visión integral del proceso educativo. La relación entre la didáctica general y las específicas, continúa siendo objeto de debate. Mientras la primera se entiende como una teoría de la intervención social en el aula, las segundas se enfocan en la enseñanza de contenidos concretos. Ambas estudian las prácticas de enseñanza, pero se diferencian en su <b>alcance</b> y su <b>enfoque</b>.
        p(data-aos="fade-left") Finalmente, los autores sostienen que es crucial establecer un diálogo entre ambas perspectivas, reconociendo su autonomía pero promoviendo la colaboración. La didáctica general puede funcionar como marco integrador, facilitando la reflexión sobre los fundamentos sociales de la enseñanza. Tanto la didáctica general como la específica, deben ser útiles y significativas para los docentes, orientadas a la mejora de la práctica pedagógica y a la construcción compartida de saberes.
    
    p.mb-4 Gutiérrez (2024), sostiene que la didáctica específica, también conocida como didáctica especial, se centra en el estudio de métodos y prácticas aplicadas a la enseñanza de diversas disciplinas. Esta rama delimita áreas del proceso educativo y desarrolla un conocimiento sistemático sobre cómo enseñar cada materia de forma efectiva. Su objetivo principal es el de atender las particularidades de la enseñanza en cada campo, adaptando estrategias a las necesidades del contenido y del alumnado.

    .bg-full-width.bg-color-2.mb-5
      .px-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").order-2
                p Uno de sus enfoques clave consiste en responder a preguntas fundamentales del proceso educativo: 
                ul.lista-ul--color
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    h5.mb-0 ¿Qué enseñar? 
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    h5.mb-0 ¿Para qué enseñar? 
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    h5.mb-0 ¿Cómo enseñar? 
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-10
                    h5.mb-0 ¿Cómo evaluar? 
                p Estas interrogantes permiten establecer diferencias metodológicas entre disciplinas, reconociendo que cada una requiere un enfoque propio basado en principios específicos.
              .col-lg-4(data-aos="zoom-in").order-1.mb-3.mb-lg-0
                img.img-fluid(src='@/assets/curso/tema1/19.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .row.mb-5
      .col-lg-4.order-lg-2.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/20.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") La aplicación práctica de la didáctica específica implica adaptar los métodos de enseñanza, según las características del área del conocimiento. Por ejemplo, si se desea transmitir un mensaje de forma más rápida, pueden utilizarse estrategias dinámicas, como el uso de cuentos, que faciliten la comprensión y el aprendizaje. Así, esta didáctica se convierte en una herramienta esencial para optimizar los procesos de enseñanza y aprendizaje (Gutiérrez, 2024).
    
        .bg-color-4.p-4(data-aos="fade-left")
          p.mb-0 Por otro lado, Camilloni (2022), destaca que la relación entre la didáctica general y las didácticas específicas no es jerárquica ni lineal. Los procesos de desarrollo de ambas, son asincrónicos y presentan distintos grados de madurez, enfoques teóricos, tradiciones investigativas y problemáticas, según la época. Esto implica que la didáctica general no es solo una síntesis de las específicas, ni estas una simple aplicación de principios generales. La interacción entre ambas es dinámica y contextualizada.

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/21.png", data-aos="zoom-in")
      .col-lg-8
        .bg-color-3.p-4.mb-5(data-aos="fade-left")
          p.mb-0 Un aporte clave en este debate es el de Wolfgang Klafki, citado por Camilloni (2022), quien formula cinco tesis fundamentales sobre la relación entre ambos tipos de didáctica. En su primera tesis, Klafki rompe con la idea tradicional de subordinación, proponiendo una relación recíproca y autónoma. Según esta visión, las didácticas específicas no derivan automáticamente de la didáctica general, sino que se nutren mutuamente, enriqueciendo el campo educativo con aportes particulares.
        p(data-aos="fade-left") A continuación, se presenta una tabla comparativa que resume las relaciones y características principales entre la didáctica general y la didáctica específica:
    
    .titulo-figura.mb-4
      h5 Tabla 1.
      span Tabla comparativa didáctica general y la didáctica específica
    .tabla-a.color-acento-botones.mb-5
      table
        thead
          tr
            th.bg-color-8.text-white.text-center Didáctica general
            th.bg-color-8.text-white.text-center Didáctica específica
        tbody.bg-color-2
          tr
            td Enfoque global sobre la enseñanza y el aprendizaje.
            td Centrada en disciplinas o áreas específicas.
          tr
            td Busca principios universales.
            td Adapta métodos, según contenidos y contextos.
          tr
            td Forma el marco teórico común.
            td Aplica estrategias concretas y particulares.
          tr
            td Influye en las específicas.
            td Se retroalimenta de lo general.
          tr
            td Mayor abstracción conceptual.
            td Mayor aplicación práctica.
    
    p.mb-4 Desde otra perspectiva Martos (2022), enfatiza el papel de la multidisciplinariedad, interdisciplinariedad y transversalidad en la educación:
    
    .bg-full-width.bg-color-9.mb-5
      .p-4.px-md-5
        .row.justify-content-center.align-items-center
          .col-lg-12
            .row.justify-content-center.align-items-center
              .col-lg-8(data-aos="fade-left").mb-3.mb-lg-0
                ul.lista-ul--color
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-9
                    p.mb-0 <b>Multidisciplinariedad:</b> cada docente enseña materias sin conexión entre contenidos.
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-9
                    p.mb-0 <b>Interdisciplinariedad:</b> se busca una articulación de contenidos bajo coordinación institucional. 
                  li.d-flex
                    i.far.fa-arrow-alt-circle-right.bg-color-9
                    p.mb-0 <b>Transversalidad:</b> se integran objetivos de distintas asignaturas desde un solo tema, algo más viable en educación primaria.
              .col-lg-4(data-aos="zoom-in")
                img.img-fluid(src='@/assets/curso/tema1/22.svg', style="max-width:486px", alt="" ).mx-auto.mx-lg-0.ms-lg-auto.mb-4.mb-lg-0
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema1/23.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") Estas dimensiones sustentan la necesidad de las didácticas especiales, cuya finalidad es garantizar el desarrollo de competencias en los estudiantes, alineadas con los objetivos curriculares. En este sentido, John Franklin Bobitt, fue un pionero al proponer currículos orientados a la inserción laboral. Actualmente, Gimeno Sacristán sostiene que el currículo debe ser una herramienta flexible, adaptable a la perspectiva didáctica del docente.
    
        .bg-color-3.p-4(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema1/24.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Martos (2022), también señala que, si bien las técnicas y recursos en las didácticas especiales son similares a los de la didáctica general (como debates, foros, exposiciones, y el uso de libros, computadoras, o equipos audiovisuales), la clave está en cómo se aplican, según la naturaleza de cada materia. Aunque en primaria, muchos contenidos pueden abordarse de forma transversal, otros exigen enfoques más específicos, lo que ha generado críticas sobre la rigidez del currículo frente a la diversidad didáctica.
    
       
    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.palermo.edu/ACI/trabajos/Alicia-Camilloni.pdf" target="_blank" rel="noopener noreferrer") de Camilloni, A. R. W. (2022). Didáctica general y didácticas específicas. Editorial Palermo. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://www.cinconoticias.com/didactica-especifica/" target="_blank" rel="noopener noreferrer") Martos, C. (2022). Didáctica específica: definición, características, campo y ejemplos de la didáctica especial. Cinco Noticias.  

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=Eknos4euloU" target="_blank" rel="noopener noreferrer") unipe: Universidad Pedagógica Nacional. (2023). El trabajo colaborativo entre investigadores y docentes en el campo de las didácticas específicas [video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema1',
  data: () => ({}),

  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
