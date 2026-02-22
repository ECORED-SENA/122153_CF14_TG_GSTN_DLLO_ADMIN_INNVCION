<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 4
      h1 Mejora continua, evaluación e informes

    .row.justify-content-center.mb-4
      .col-md-7.col-lg-4.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/tema4/img-1.svg')
      .col-lg-8
        p.mb-4 Siempre se busca fortalecer la gestión organizacional y el análisis de datos, entregando herramientas que le serán útiles para la planificación, el desarrollo y la verificación, pero ante todo a la mejora continua; esta última vista desde planes de trabajo o acciones correctivas, los cuales son provenientes de iniciativas propias por mejorar el proceso, de resultados desfavorables en la evaluación de indicadores de eficiencia, efectividad o eficacia que se empleen para la medición del proceso.
        .cajon.color-primario.p-4.fnd-3
          p.mb-0 También suelen ser producto de los hallazgos, las recomendaciones o aspectos por mejorar que surgen en los diferentes comités organizacionales, asimismo, otra de la fuente de mejora continua puede darse en las órdenes de la alta dirección o por los diferentes métodos de control que se empleen en la organización. 
    
    .row.justify-content-center.align-items-center.mb-5
      .col-md-6.col-lg-8
        p De esta forma, la mejora continua, como lo expresa la misma denominación, es un método permanente, orientado a generar valor agregado a la gestión realizada o corregir defectos de la gestión del proceso, debiéndose ejecutar mediante mecanismos que identifiquen las problemáticas y que respalden los resultados finales, los cuales deben ser reflejados en los diferentes informes de gestión de las empresas. 
      .col-md-6.col-lg-4.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema4/img-2.svg')

    ul.lista-ul--color.mor.fa-lista.mb-4
      li 
        i.fas.fa-square
        span.mb-0.h3.text-black No conformidades y acciones correctivas
    
    .row.justify-content-center.mb-4
      .col-md-7.col-lg-4.mb-3.mb-lg-0
        img(src='@/assets/curso/temas/tema4/img-3.svg')
      .col-lg-8
        p Es necesario apoyarnos en el numeral 10.2 de la norma ISO 9001 versión 2015, donde se orienta en el manejo de las no conformidades; esto se traduce como la falla o error en algunas de las actividades que se gestionan, y el tratamiento de mejora continua va orientado a la implementación de acciones correctivas, partiendo de cuando se presenta una no conformidad en la empresa, se debe tomar la acción necesaria e inmediata, para investigar qué ha ocurrido y corregirlo, con el objetivo de evitar que casos similares se presenten a futuro y buscando mitigar el impacto de lo ocurrido.
        .cajon.color-primario.p-4.fnd-3
          p.mb-0 ¿Qué hacer ante las no conformidades? Toda empresa, a través de los responsables del proceso y del control de este, debe tomar medidas inmediatas para intervenir o corregir sus no conformidades, esto buscando contener el impacto de las falencias, mientras se investiga más sobre su origen, informando de la no conformidad presentada, a niveles de control necesarios, vislumbrando la información sobre los efectos potenciales o reales en el producto o servicio esté afectando. 

    .row.justify-content-between.mb-4
      .col-lg-8
        p Ahora bien, para el tratamiento, se debe determinar su causa, porque si no se conoce el origen del problema, no se podrán erradicar las causas de las no conformidades. Pueden utilizarse varios métodos para identificación de las causas raíz.
        p Remítase el material complementario y explore el artículo #[b “10 técnicas de análisis de causa raíz de los desperdicios de la calidad para eliminarlos”] a través del enlace que allí se deja.
      .col-lg-4.d-none.d-lg-block
        img(src='@/assets/curso/temas/tema4/img-4.svg')

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10
        .cajon.color-acento-botones.p-4.fnd-2
          p #[b ¡Nota importante!]
          p.mb-0  Cualquiera de las técnicas que se utilicen, son favorables para la identificación de causas, pero las mismas requieren que las personas que las desarrollen, las apliquen con transparencia y objetividad.
   
    p.mb-4 Pero el trabajo no termina ahí, posterior a identificar las causas, es necesario determinar qué acciones concretas se van a desarrollar, un ejemplo es el método diseñado por #[em Edward Deming,] conocido como el ciclo PHVA, el cual estudiaremos a continuación, enfocado en la temática que estamos abordando.
    .row.justify-content-center.align-items-center.mb-5
      .col-lg-8
        ImagenInfografica.color-acento-botones
          template(v-slot:imagen)
            figure
              img(src='@/assets/curso/temas/tema4/img-5-.svg')
          .tarjeta.color-secundario.fnd-4-.p-3(x="49.8%" y="11.2%" numero="+")
            p.mb-0 Se parte de una PLANIFICACIÓN para gradualmente ir corrigiendo y reduciendo los efectos no deseados.
          .tarjeta.color-secundario.fnd-4-.p-3(x="89%" y="52.8%" numero="+")
            p.mb-0 En la secuencia del HACER, se desarrollan actividades que logren irradiar de manera integral la solución de las falencias, la eficacia de estas acciones y los efectos potenciales que tengan sobre los procesos, repercutirán de manera directa en futuras aplicaciones del proceso antes señalado.
          .tarjeta.color-secundario.fnd-4-.p-3(x="49.8%" y="89%" numero="+")
            p.mb-0 La etapa de VERIFICACIÓN permitirá ejercer los controles oportunos, con el objetivo que las que falencias identificadas sean subsanadas y que no se repitan en futuras ocasiones.
          .tarjeta.color-secundario.fnd-4-.p-3(x="11.2%" y="52.8%" numero="+")
            p.mb-0 Se concluye el ciclo con el ACTUAR o también conocido como la etapa de AJUSTAR, es acá donde de manera particular, evaluamos la eficiencia de las actividades relacionadas con la acción correctiva implementada y se determina el cierre de la acción o si se requiere el ajuste a la acción correctiva.

    ul.lista-ul--color.mor.mb-4
      li 
        i.fas.fa-square
        span.mb-0.h3.text-black Indicadores de gestión

    p Por otra parte, la medición de resultados en las entidades o empresas es necesaria para poder estar a la vanguardia de las necesidades o servicios que se desarrollan en un mundo de oportunidades, que a diario es cambiante, y ponderar la productividad y el impacto, son componentes necesarios hoy en día, por ende, el enfoque del aumento de los resultados siempre debe ser la prioridad. 
    p.mb-4 Los métodos de medición son comúnmente conocidos como indicadores y estos parten de la utilidad para la que se crean, relacionando aspectos de importancia, como:
    
    .row.justify-content-center.mb-4
      .col-lg-3.col-md-6.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema4/img-6.svg' alt='')
          .tarjeta.color-secundario.w-100.fnd-6
            .text-center.p-4
              p.mb-0 Tomar decisiones en todos los niveles.
      .col-lg-3.col-md-6.mb-4
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema4/img-7.svg' alt='')
          .tarjeta.color-secundario.w-100.fnd-5
            .text-center.p-4
              p.mb-0 Medir el desempeño de procesos y de personas.
      .col-lg-3.col-md-6.mb-4       
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema4/img-8.svg' alt='')
          .tarjeta.color-secundario.w-100.fnd-6
            .text-center.p-4
              p.mb-0 Comparar y hacer seguimiento de la gestión.         
      .col-lg-3.col-md-6         
        .tarjeta-avatar
          img(src='@/assets/curso/temas/tema4/img-9.svg' alt='')
          .tarjeta.color-secundario.w-100.fnd-5
            .text-center.p-4
              p.mb-0 Medir la eficacia, la eficiencia y la efectividad de la entidad o la empresa.      

    p.mb-4 Teniendo en cuenta la pertinencia e importancia de la medición, es necesario abordar los tipos de indicadores y las características que deben contener estos elementos de medición, tema que se tratará en el siguiente video.
    
    .mb-4
      figure
        .video
          iframe(width="560" height="315" src="https://www.youtube.com/embed/eN4UvzBrZ34" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Video. Tipos y catacterísticas de los indicadores

    p Ahora bien, comprendiendo la temática relacionada con los indicadores, surge la necesidad de percibir cómo se puede crear este tipo de herramientas de medición, con el objetivo de ayudar a la medición en su entidad o empresa.
    p.mb-4 Ahora vemos las siguientes recomendaciones para la creación de indicadores: 
    
    .row.justify-content-center.mb-5
      SlyderA.fnd-4.fl-a.p-5(tipo="b")
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-10.svg')
          .col-md-8
            p Identifique el objetivo del proceso y la finalidad del objetivo.
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-17.svg')
          .col-md-8
            p Identifique las variables a medir (cualitativas o cuantitativas).
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-18.svg')
          .col-md-8
            p Identifique las fuentes de las variables (cualitativas o cuantitativas).
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-19.svg')
          .col-md-8
            p Defina la fórmula del indicador, realice ejercicios prácticos previamente (variable medida/variable esperada).
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-20.svg')
          .col-md-8
            p Clasifique el indicador:
            ul.lista-ul--color.nar.fa-lista
              li 
                i.fas.fa-check
                p.mb-0
                  b Eficacia: 
                  | mide los resultados alcanzados frente a los resultados esperados.
              li 
                i.fas.fa-check
                p.mb-0
                  b Eficiencia: 
                  | mide los recursos utilizados frente a resultados obtenidos, o también mide la relación entre los resultados alcanzados frente a los recursos disponibles. 
              li 
                i.fas.fa-check
                p.mb-0
                  b Efectividad:
                  |  mide el impacto del indicador frente al cumplimiento del objetivo o también se puede ver como la combinación entre la eficiencia y la eficacia.
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-21.svg')
          .col-md-8
            p Fije una meta: se puede dar espacios para medición de línea base.
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-22.svg')              
          .col-md-8
            p Determine la periodicidad de medición (semana, quincenal, mensual, semestral, o anual).      
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-23.svg')
          .col-md-8
            p Delimite los rangos de evaluación: ejemplo, de 0 a 60 deficiente, de 60,1 a 75 aceptable, de 75,1 a 80 bueno, de 85,1 a 100, de 100,1 en adelante es sobresaliente.  
        .row.justify-content-center.align-items-center
          .col-md-4.mb-4.mb-md-0.p-y-5
            img.img-106(src='@/assets/curso/temas/tema4/img-24.svg')
          .col-md-8
            p Identifique y asigne responsables del indicador y de sus variables. 

    ul.lista-ul--color.mor.mb-4
      li 
        i.fas.fa-square
        span.mb-0.h3.text-black Informes de gestión y tipos de informes 

    p.mb-4 Para el desarrollo de informes de gestión es importante que se integren todas las características y métodos expuestos, pero con la claridad en qué punto y momento se va a realizar el informe.

    .row.justify-content-center.mb-5
      .col-lg-10
        .bloque-texto-a.color-primario.p-4.p-md-5.fnd-7
          .row.m-0.align-items-center.justify-content-between
            .col-lg-4
                p.text-black Por ejemplo, algunos informes que se desarrollan en la gestión del talento humano son:  
            .col-lg-8.mb-4.mb-lg-0
              .bloque-texto-a__texto.p-4.mb-sm-3
                ul.lista-ul--color.nar.fa-lista
                  li 
                    i.fas.fa-check
                    span.mb-0 Informe de resultados de alguna de las fases del ciclo de la gestión del proceso.
                  li 
                    i.fas.fa-check
                    span.mb-0 Informes de supervisión.
                  li 
                    i.fas.fa-check
                    span.mb-0 Informes de las evaluaciones del desempeño laboral.
                  li 
                    i.fas.fa-check
                    span.mb-0 Informes de gestión del proceso y la medición de sus indicadores.
                  li 
                    i.fas.fa-check
                    span.mb-0 Informes de resultados de planes de mejoramiento.
 
    p Para el desarrollo de este tipo de entregas de información, recuerde tener en cuenta los elementos determinantes para el análisis CAC (Calidad de la información, Aplicación de técnicas y Comunicación correcta de los resultados).

    p.mb-4 Un ejemplo interesante para el desarrollo de un informe es el de resultados de un plan de mejoramiento, para lo cual damos las siguientes consideraciones que deben integrar la composición del informe:

    .row.justify-content-center
      .col-lg-9
        PasosA.color-acento-contenido.mb-5(tipo="n")
          .row.align-items-center
            .col-md-2.col-5
              figure.mb-3
                img.img-50(src='@/assets/curso/temas/tema4/img-25.svg')
            .col-md-10.mb-4.mb-md-0
              p Se identifica un hallazgo por parte de un órgano externo a la entidad o empresa.
          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p.text-left Dado el hallazgo, se genera un ciclo de gestión de la mejora, por ende, el tratamiento de este hallazgo genera una acción correctiva y para la creación de esta, se revisan y aplican las técnicas para identificar la causa raíz que generó la no conformidad.
            .col-md-2.col-5
              figure
                img.img-50(src='@/assets/curso/temas/tema4/img-26.svg')
          .row.align-items-center
            .col-md-2.col-5
              figure.mb-3
                img.img-50(src='@/assets/curso/temas/tema4/img-27.svg')
            .col-md-10.mb-4.mb-md-0
              p Se plantea un tratamiento para subsanar la novedad mediante el desarrollo del ciclo PHVA, de acuerdo con los parámetros de la entidad o empresa donde se labora.
          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p.text-left Se ejecutan las tareas del plan de mejoramiento.
            .col-md-2.col-5
              figure
                img.img-50(src='@/assets/curso/temas/tema4/img-28.svg')
          .row.align-items-center
            .col-md-2.col-5
              figure.mb-3
                img.img-50(src='@/assets/curso/temas/tema4/img-29.svg')
            .col-md-10.mb-4.mb-md-0
              p Se verifica y ajusta de ser necesario, las actividades desarrolladas.
          .row.align-items-center
            .col-md-10.mb-4.mb-md-0
              p.text-left Se comunica a la alta dirección, a los entes y fases de control que correspondan, el resultado de los planes de mejoramiento, con características de objetividad, claridad, transparencia y organización de resultados.
            .col-md-2.col-5
              figure
                img.img-50(src='@/assets/curso/temas/tema4/img-30.svg')

    .row.justify-content-center.align-items-center
      .col-lg-10
        .cajon.color-acento-botones.p-4.fnd-2
          p.mb-0 Recuerde explorar los demás recursos que se encuentran disponibles en este componente formativo; para ello, diríjase al menú principal, donde encontrará la síntesis, una actividad didáctica para reforzar los conceptos estudiados, material complementario, entre otros.


</template>

<script>
export default {
  name: 'Tema3',
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
