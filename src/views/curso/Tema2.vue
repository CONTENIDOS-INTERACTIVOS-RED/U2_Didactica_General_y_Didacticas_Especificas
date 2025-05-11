<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(:subTitulo="'2. Criterios de las didácticas específicas'")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.overflow-hidden

    .row.mb-5
      .col-lg-4.order-2
        figure
          img(src="@/assets/curso/tema2/1.png", data-aos="zoom-in")
      .col-lg-8.order-1.mb-3.mb-lg-0
        .bg-color-1.p-4.mb-3(data-aos="fade-left")
          .row.align-items-start
            .col-lg-auto
              img(src="@/assets/curso/tema2/2.svg", style="max-width: 90px").mx-auto
            .col-lg
              p.mb-0 Según Gutiérrez (2024), las didácticas específicas constituyen un enfoque pedagógico que adapta métodos y estrategias de enseñanza a las particularidades de cada disciplina o área del conocimiento. Su objetivo principal es garantizar que los procesos de enseñanza-aprendizaje sean efectivos y pertinentes, considerando tanto las características del contenido como las necesidades de los estudiantes.
        p(data-aos="fade-left") Para lograrlo, se establecen diversos criterios fundamentales que orientan su aplicación, destacando la contextualización disciplinar, la adecuación al nivel educativo, la flexibilidad metodológica y la evaluación contextualizada. A continuación, se presenta una tabla con los principales criterios, según Gutiérrez (2024):
    
    .bg-full-width.bg-color-info.mb-5
      .p-4.p-md-5
        .row.justify-content-center.align-items-center
          .col-lg-6
            ImagenInfografica.color-secundario
              template(v-slot:imagen)
                figure
                  img(src='@/assets/curso/tema2/3.svg', alt='', style="max-width: 1106px;").mx-auto
    
              .bg-color-white.box-shadow.p-3(x="61%" y="45%" numero="+")
                h5 01. Contextualización disciplinar
                p Adaptación de métodos y estrategias a las particularidades de cada disciplina (ciencias, matemáticas, lenguas, etc.), garantizando la pertinencia del enfoque.
    
              .bg-color-white.box-shadow.p-3(x="93%" y="45%" numero="+")
                h5 02. Adecuación al nivel educativo
                p Ajuste a las características del nivel educativo (inicial, primaria, secundaria, superior), considerando el desarrollo cognitivo, emocional y social del alumnado.
    
              .bg-color-white.box-shadow.p-3(x="26%" y="92%" numero="+")
                h5 03. Desarrollo de competencias
                p Integración de conocimientos, habilidades y actitudes propias de cada disciplina para fomentar aprendizajes aplicables en contextos reales.
    
              .bg-color-white.box-shadow.p-3(x="60%" y="92%" numero="+")
                h5 04. Flexibilidad metodológica
                p Uso de diversas estrategias didácticas que se adapten a los contenidos, al contexto y a las necesidades del grupo, favoreciendo procesos dinámicos y significativos.
    
              .bg-color-white.box-shadow.p-3(x="93%" y="92%" numero="+")
                h5 05. Evaluación contextualizada
                p Diseño de instrumentos de evaluación que respondan a los objetivos específicos de aprendizaje de la disciplina, asegurando la comprensión y aplicación de saberes.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/4.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") Por su parte, Camilloni (2022), complementa esta perspectiva señalando que existen múltiples formas de clasificar y analizar los criterios de enseñanza, debido a la naturaleza cambiante de la sociedad y del conocimiento. El surgimiento de nuevos métodos pedagógicos, grupos estudiantiles diversos, objetivos educativos renovados y formas actuales de concebir el aprendizaje obliga a revisar y adaptar permanentemente estos enfoques.
    
        .bg-color-2.p-4(data-aos="fade-left")
          p.mb-0 Así, los criterios didácticos deben entenderse como estructuras abiertas y flexibles, capaces de evolucionar en función de los cambios culturales, sociales y tecnológicos. Camilloni aclara que, aunque no es posible abordar todos los criterios existentes, en los siguientes apartados se explicarán algunos de los más relevantes dentro del contexto educativo contemporáneo.
    
    h2.mb-5(data-aos="fade-left") Didácticas específicas por niveles educativos

    .bg-color-3.mb-5(data-aos="fade-up")
      .row.justify-content-center.align-items-center
        .col-lg-auto.order-2
          figure
            img(src='@/assets/curso/tema2/5.png', alt='')
        .col-lg.order-1.mb-3.mb-lg-0
          .p-4
            p.mb-0(data-aos="fade-up") La didáctica específica se organiza y adapta para abordar las particularidades de cada etapa educativa, con el objetivo de responder a las necesidades y características únicas de los estudiantes en cada nivel de su desarrollo. A continuación, se amplían estas divisiones, destacando ejemplos concretos para una mejor comprensión.
    
    h2.mb-5(data-aos="fade-left") a- Didáctica de la educación inicial

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/6.png", data-aos="zoom-in")
      .col-lg-8
        p.mb-5(data-aos="fade-left") La didáctica en la educación inicial es un pilar fundamental para el desarrollo integral de los niños. Esta etapa sienta las bases para aprendizajes futuros. Las estrategias pedagógicas deben diseñarse cuidadosamente para estimular todas las áreas del desarrollo infantil. Se abordan habilidades como la comunicación verbal y no verbal, la motricidad fina y gruesa, y la socialización temprana (Camilloni, 2022).
    
        .bg-color-1.p-4(data-aos="fade-left")
          p.mb-0 El ambiente de aprendizaje cumple un rol esencial. Un espacio colorido, seguro y estimulante invita a los niños a participar activamente, despierta su curiosidad y fomenta su autonomía. Es importante que el entorno promueva la exploración, la expresión de ideas, el respeto y la colaboración entre pares (Alonso Arija, 2021).
    
    .bg-full-width.bg-color-5
      .p-4.p-md-5
        .row.mb-5
          .col-lg-4.mb-3.mb-lg-0.order-lg-2
            figure
              img(src="@/assets/curso/tema2/7.png", data-aos="zoom-in")
          .col-lg-8.order-lg-1
            p(data-aos="fade-left") Esta didáctica no se limita al juego. También requiere una planificación y evaluación cuidadosa, con actividades ajustadas al ritmo y los intereses individuales de cada niño. La evaluación debe ser continua, utilizando herramientas como la observación directa, el registro de anécdotas y la elaboración de portafolios (Camilloni, 2022). Un aspecto clave es la formación del educador. Este debe contar con una base pedagógica sólida para diseñar estrategias efectivas y crear ambientes de aprendizaje seguros y enriquecedores.
            p(data-aos="fade-left") Además, debe mantenerse actualizado con las investigaciones y tendencias recientes para ofrecer una educación de calidad (Alonso Arija, 2021).

        div.row.justify-content-center.align-items-stretch
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/8.svg" alt="" style="width: 90px")
              h5.text-center Áreas del desarrollo
              p.mb-0.text-center Comunicación, motricidad fina y gruesa, socialización (Camilloni, 2022).
        
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/9.svg" alt="" style="width: 90px")
              h5.text-center Ambiente de aprendizaje
              p.mb-0.text-center Espacio seguro, colorido y estimulante que promueve la autonomía, curiosidad y colaboración. (Alonso Arija, 2021).
        
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/10.svg" alt="" style="width: 90px")
              h5.text-center Planificación y evaluación
              p.mb-0.text-center Actividades adaptadas al ritmo e intereses del niño; evaluación continua mediante observación, registros y portafolios (Camilloni, 2022).
          div.col-lg-3.mb-3(data-aos="zoom-in-up")
            div.bg-color-white.box-shadow.px-4.py-5.h-100
              img.mx-auto.d-block.mb-4(src="@/assets/curso/tema2/11.svg" alt="" style="width: 90px")
              h5.text-center Rol del educador
              p.mb-0.text-center Formación pedagógica sólida, estrategias efectivas y actualización constante (Alonso Arija, 2021).
    
    h2.mb-5(data-aos="fade-left") b- Didáctica de la educación primaria

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/12.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") En la educación primaria, la didáctica busca que los niños adquieran conocimientos básicos en lectura, escritura, matemáticas y ciencias. Se usan estrategias activas y colaborativas que invitan a los estudiantes a participar y pensar por sí mismos (Camilloni, 2022).
    
        .bg-color-4.p-4.mb-3(data-aos="fade-left")
          p.mb-0 Por ejemplo, en matemáticas, se pueden hacer actividades en grupo como calcular el cambio en una compra ficticia o armar un presupuesto para un evento. Esto ayuda a entender los contenidos y a desarrollar habilidades como la comunicación y el trabajo en equipo (Johnson, Johnson & Holubec, 2014). Además, los proyectos que combinan distintas materias, como construir una maqueta con ideas de ciencias y arte, promueven la creatividad y el aprendizaje integral.
        p(data-aos="fade-left") <b>El docente tiene un rol clave:</b> debe crear un ambiente seguro, proponer actividades variadas, motivar la participación y adaptar su enseñanza a las necesidades de cada estudiante. También guía el desarrollo del pensamiento crítico y la resolución de problemas (Tomlinson, 2014).
    
    .bg-full-width.bg-color-5
      .p-4.p-md-5
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0
    
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/14.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Áreas principales
                p.text-center Lectura, escritura, matemáticas, ciencias.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/15.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Estrategias usadas
                p.text-center Actividades grupales, proyectos, resolución de problemas.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/16.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Habilidades que se desarrollan
                p.text-center Pensamiento crítico, trabajo en equipo, creatividad.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/17.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Rol del docente
                p.text-center Guía, motivador, adaptador de estrategias, evaluador continuo.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/18.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Objetivo general
                p.text-center Construir una base sólida para el aprendizaje futuro.
          .col-lg-4
            figure
              img(src='@/assets/curso/tema2/13.png', alt='')
        
        h2.mb-5(data-aos="fade-left") c- Didáctica de la educación secundaria

        .row
          .col-lg-4.mb-3.mb-lg-0
            figure
              img(src="@/assets/curso/tema2/19.png", data-aos="zoom-in")
          .col-lg-8
            p.mb-5(data-aos="fade-left") En la secundaria, la didáctica se enfoca en el desarrollo de competencias específicas en diversas disciplinas, preparando a los estudiantes para la educación superior o el mundo laboral (Camilloni, 2022). Aquí se consolidan los aprendizajes de la primaria y se profundiza en la investigación, el análisis crítico y la síntesis de información.
        
            .bg-color-2.p-4(data-aos="fade-left")
              p.mb-0 Se aplican metodologías activas centradas en el estudiante, que fomentan la participación y el aprendizaje significativo. Por ejemplo, en ciencias, los alumnos pueden diseñar experimentos sencillos para comprobar hipótesis, documentando observaciones y conclusiones. Esto fortalece habilidades de investigación, análisis y comunicación (Darling-Hammond, 2010).
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema2/20.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") En el área de humanidades, se promueven debates estructurados sobre temas sociales o históricos, lo que estimula el pensamiento crítico y la expresión oral. También se incentiva a los estudiantes para que integren conocimientos de distintas asignaturas para resolver problemas complejos, como analizar el impacto de un hecho histórico en la actualidad o proponer soluciones a problemáticas sociales (Darling-Hammond, 2010).
    
        .bg-color-3.p-4(data-aos="fade-left")
          p.mb-0 El docente actúa como guía y mentor, adaptando sus estrategias a las características de cada grupo, promoviendo la autonomía, el pensamiento crítico y el desarrollo de la responsabilidad personal. Su función es clave para acompañar a los estudiantes en la toma de decisiones, sobre su futuro académico y profesional.
    
    p.mb-4 La didáctica en esta etapa tiene un impacto profundo, dado que no solo busca transmitir conocimientos, sino formar personas capaces de pensar, argumentar, investigar y actuar con responsabilidad (Camilloni, 2022).

    .row.align-items-start.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/21.png", alt="").mb-4.mb-lg-0
      .col-lg-8
    
        AcordionA(tipo="b")
          .div(titulo="Enfoque principal")
            p Desarrollo de competencias específicas y preparación para estudios superiores o el trabajo.
    
          .div(titulo="Estrategias comunes")
            p Experimentos, debates, proyectos interdisciplinarios.
    
          .div(titulo="Habilidades desarrolladas")
            p Pensamiento crítico, investigación, análisis, comunicación, síntesis de información.
    
          .div(titulo="Rol docente")
            p Guía y mentor, fomenta la autonomía y la responsabilidad.
          .div(titulo="Impacto formativo")
            p Base para el éxito académico y profesional.
    
    h2.mb-5(data-aos="fade-left") d-	Didáctica de la educación superior y universitaria

    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0.order-lg-2
        figure
          img(src="@/assets/curso/tema2/22.png", data-aos="zoom-in")
      .col-lg-8.order-lg-1
        p.mb-5(data-aos="fade-left") En este nivel, la didáctica se orienta a formar profesionales altamente capacitados en áreas específicas. Las estrategias se enfocan en el aprendizaje activo, la investigación y la innovación (Camilloni, 2022; Hmelo-Silver, 2004).
    
        .bg-color-1.p-4(data-aos="fade-left")
          p.mb-0 Se emplean metodologías como el aprendizaje basado en proyectos y el análisis de casos. Por ejemplo, estudiantes de derecho pueden participar en simulaciones de juicios para practicar su argumentación legal. En carreras científicas, se desarrollan proyectos de investigación que contribuyen al conocimiento del área. Estas estrategias permiten aplicar teoría a situaciones reales, promoviendo la toma de decisiones, el pensamiento crítico y habilidades prácticas.
    
    .row.mb-5
      .col-lg-4.mb-3.mb-lg-0
        figure
          img(src="@/assets/curso/tema2/23.png", data-aos="zoom-in")
      .col-lg-8
        p(data-aos="fade-left") También se impulsa la participación en seminarios y congresos, donde los estudiantes amplían su formación, comparten ideas, y se vinculan con profesionales de su campo, estimulando la autonomía, la innovación y el compromiso con su disciplina.
    
        .bg-color-2.p-4.mb-5(data-aos="fade-left")
          p.mb-0 El docente cumple un rol de mentor y facilitador, diseñando actividades acordes a los intereses y necesidades del grupo. Además de guiar el aprendizaje, debe promover la responsabilidad, el pensamiento crítico y la capacidad de los estudiantes para actuar como futuros líderes en sus campos profesionales (Hmelo-Silver, 2004).
        p(data-aos="fade-left") La didáctica en este nivel tiene un impacto clave, puesto que prepara a los estudiantes para liderar, investigar e innovar en sus respectivas áreas, y para contribuir activamente al desarrollo de la sociedad (Camilloni, 2022).

    .bg-full-width.bg-color-5
      .p-4.p-md-5
        .row.justify-content-center.mb-5
          .col-lg-8.mb-3.mb-lg-0
            SlyderF(columnas="col-12 col-lg-6")
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/25.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Objetivo principal
                p.text-center Formación de profesionales competentes y comprometidos.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/26.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Estrategias claves
                p.text-center Aprendizaje basado en proyectos, análisis de casos, simulaciones, investigaciones.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/27.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Ámbitos de aplicación
                p.text-center Derecho (juicios simulados), ciencias (proyectos de investigación), seminarios, congresos.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/28.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Habilidades desarrolladas
                p.text-center Toma de decisiones, pensamiento crítico, comunicación, innovación.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/29.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Rol docente
                p.text-center Mentor, guía, diseñador de experiencias formativas avanzadas.
              .bg-color-white.p-4.h-100.shadow-app
                img(src='@/assets/curso/tema2/30.svg' alt='AvatarTop' , style="max-width: 90px").mx-auto.mb-3
                h4.text-center.mb-4 Impacto formativo
                p.text-center Formación de líderes, impulso a la innovación, preparación para el mundo profesional.
          .col-lg-4
            figure
              img(src='@/assets/curso/tema2/24.png', alt='')
        
        

    .bg-full-width.border-top.color-primario
      .p-4.p-md-5
        h2(data-aos="fade-left") MATERIAL COMPLEMENTARIO
        .row.material-complementario
          .col-12.col-md-6.col-lg-7
            p Los invitamos a explorar el material complementario de este curso, en esta sección encontrará recursos que le permitirán profundizar  y enriquecer su aprendizaje en los temas tratados en esta unidad.

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://uvadoc.uva.es/bitstream/handle/10324/51451/TFG-L3005.pdf?sequence=1" target="_blank" rel="noopener noreferrer") Alonso Arija, N. (2021). El juego como recurso educativo: teorías y autores de renovación pedagógica. Universidad de Valladolid. 

            p.d-flex.my-4
              img.me-3(src='@/assets/componentes/link.svg' :style="{'max-width':'16px'}")
              a(href="https://didacticasespecificass.blogspot.com/2020/12/didacticas-especificas.html " target="_blank" rel="noopener noreferrer") DIDÁCTICAS ESPECÍFICAS. (2020). IMPORTANCIA DE LAS DIDÁCTICAS ESPECÍFICAS.  

            p.d-flex.my-4
              img.me-3(src='@/assets/template/icono-yt.svg' :style="{'max-width':'16px'}")
              a(href="https://www.youtube.com/watch?v=5_Qk5OjjI_U " target="_blank" rel="noopener noreferrer") ITED Instituto. (2021). Live: 5 estrategias didácticas para docentes universitarios [video]. YouTube. 

          .col-12.col-md-6.col-lg-3.offset-lg-1
            figure
              img(src='@/assets/componentes/material-complementario.svg', alt='')

</template>

<script>
export default {
  name: 'Tema2',
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
}
</script>

<style lang="sass"></style>
