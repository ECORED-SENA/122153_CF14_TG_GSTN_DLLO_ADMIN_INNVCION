<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal.color-acento-contenido
      .titulo-principal__numero
        span 2
      h1 Parámetros estadísticos  

    .row.justify-content-center.align-items-center.mb-4
      .col-md-5.col-lg-4.mb-3.mb-lg-0
          img(src='@/assets/curso/temas/tema2/img-1.svg')
      .col-md-7.col-lg-8
        p Un parámetro estadístico, permite la lectura, la interpretación y la síntesis de los datos objeto de estudio, por lo cual distribuiremos los parámetros en tres grandes componentes que, de acuerdo con las denominaciones estadísticas, se subdividen bajo los conceptos abordados en la siguiente figura:

    .row.justify-content-center.align-items-center.mb-5
      .col-lg-10
        .titulo-sexto.color-acento-contenido(data-aos='fade-right')
          p.mb-0 #[b Figura 1.] Tipos de parámetros estadísticos
        figure
          img(src='@/assets/curso/temas/tema2/img-2.svg' alt="Mapa conceptual que representa la derivación de los 3 parámetros estadísticos los cuales son: - Centralización: media aritmética, mediana y moda. - Posición: cuartiles, deciles y percentiles. - Dispersión: rango o recorrido, desviación media y varianza.")          

    p.mb-5 Ampliemos la información sobre cada uno de ellos.


    ul.lista-ul--color.mor.mb-4
      li 
        i.fas.fa-square
        span.mb-0.h3.text-black Parámetros de centralización

    p Los parámetros de centralización indican en torno a qué valor o criterio central se distribuyen los datos obtenidos, para lo cual se establecen tres criterios, la media aritmética, la mediana y la moda. Cada uno de estos parámetros nos permiten interpretar la información de acuerdo con las características específicas para el análisis de los datos.
    p.mb-4 A continuación, se explica cada uno de estos criterios:

    TabsC.color-acento-contenido.mb-5
      .py-3.py-md-4(titulo="Media aritmética")
        .row.justify-content-center    
          .col-md-6.col-11.mb-4.mb-md-0
              figure.px-3
                img(src='@/assets/curso/temas/tema2/img3.svg')                     
          .col-md-6.col-11.mb-4.mb-md-0
            p.mb-3 La media es la suma de todos los datos divididos por el número de datos.
              br
              | Ejemplo: 
            figure
              img.img-66(src='@/assets/curso/temas/tema2/img-a.svg')   
            p.mb-0 Tres es la cantidad de datos.
            figure.img-75
              img.img-75(src='@/assets/curso/temas/tema2/img-b.svg')  
            p.mb-0 Entonces, la media es 2.
      .py-3.py-md-4(titulo="Mediana")
        .row.justify-content-center    
          .col-md-6.col-11.mb-4.mb-md-0
              figure.px-3
                img(src='@/assets/curso/temas/tema2/img4.svg')                     
          .col-md-6.col-11.mb-4.mb-md-0
            p.mb-3 Representa el valor de la variable de la posición central en un conjunto de datos ordenados. 
            p.mb-0 Ejemplo: 
            p 1, 5 y 10
            p La mediana es la posición central, en este caso corresponde a 5.
      .py-3.py-md-4(titulo="Moda")
        .row.justify-content-center    
          .col-md-6.col-11.mb-4.mb-md-0
              figure.px-3
                img(src='@/assets/curso/temas/tema2/img-5.svg')                     
          .col-md-6.col-11.mb-4.mb-md-0
            p.mb-3 Es el valor de la variable con mayor frecuencia absoluta.
            p Ejemplo: 
              br
              | En los números 3, 2, 3, 4, 5, 3, 7, 8, 7 y 10, los números 2, 4, 5, 8 y 10 aparecen una vez cada uno, el número 3 aparece en tres ocasiones y el número 7 aparece en dos oportunidades. Es así como la moda estadística es el número 3.
    
    
    ul.lista-ul--color.mor.mb-4
      li 
        i.fas.fa-square
        span.mb-0.h3.text-black Parámetros de posición
    
    p Consta de dividir los datos en grupos con el mismo número de datos recopilados. Para esto es necesario organizar la información de datos de menor a mayor, y para su interpretación se organiza en criterios conocidos como cuantiles, los cuales son variables de intervalos en los que se dividen los datos.
    p.mb-4 Algunos ejemplos son: 

    SlyderA.fnd-4.fl-a.mb-5.p-5(tipo="b")
      .row.justify-content-center
        .col-lg-6.mb-4.mb-md-0.p-y-5
          h3 Percentiles
          p Es la división de una serie de datos en 100 partes iguales; teniendo un acumulado de datos que nos da el número 700, se nos pide ubicar el percentil 9 y percentil 50, esto equivale a dividir el dato obtenido en 100 puntos de posición (700/100), que en este caso es el número 700 en 100 partes; ubicando así el percentil 1, el cual es equivalente al número 7, sumando o multiplicando cada percentil, es decir, llegando a la posición del percentil 9, el cual se ubica en el número 63, y el resultado del percentil 50, es el número 350.         
        .col-md-10
          img(src='@/assets/curso/temas/tema2/img-6.svg')
      .row.justify-content-center
        .col-lg-6.mb-4.mb-md-0.p-y-5
          h3 Deciles 
          p Es la división de una serie de datos en 10 partes iguales; teniendo un acumulado de datos que nos da el número 1250, se nos pide ubicar el decil 3 y decil 6, esto equivale a dividir el dato obtenido en 10 puntos de posición (1250/10), que en este caso es el número 1250 en 10 partes; ubicando así el decil 1, el cual es equivalente al número 125, sumando o multiplicando cada decil, es decir, llegando a la posición del decil 3, el cual se ubica en el número 375, y del resultado del decil 6, es el número 750.         
        .col-md-10
          img(src='@/assets/curso/temas/tema2/img-7.svg')
      .row.justify-content-center
        .col-lg-6.mb-4.mb-md-0.p-y-5
          h3 Quintiles
          p Es la división de una serie de datos en 5 partes iguales; teniendo un acumulado de datos que nos da el número 250, se nos pide ubicar el primer y el cuarto quintil, esto equivale a dividir el dato obtenido en 5 puntos de posición (250/5), que en este caso es el número 250 en 5 partes; ubicando así el primer quintil, el cual es equivalente al número 50, sumando o multiplicando cada quintil, es decir, llegando a la posición del cuarto quintil es el número 200.         
        .col-md-10
          img(src='@/assets/curso/temas/tema2/img-8.svg')
      .row.justify-content-center
        .col-lg-6.mb-4.mb-md-0.p-y-5
          h3 Cuartiles
          p Es la división de una serie de datos en 4 partes iguales; teniendo un acumulado de datos que nos da el número 880, se nos pide ubicar el segundo y el tercer cuartil, esto equivale a dividir el dato obtenido en 4 puntos de posición (880/4), que en este caso es el número 880 en 4 partes; ubicando así el primer cuartil, el cual es equivalente al número 220, sumando o multiplicando cada quintil, es decir, llegando a la posición del segundo cuartil, que es el número 440 y el tercer cuartil que es el número 660.         
        .col-md-10
          img(src='@/assets/curso/temas/tema2/img-9.svg')

    ul.lista-ul--color.mor.mb-4
      li 
        i.fas.fa-square
        span.mb-0.h3.text-black Parámetros de dispersión 

    p Son establecidos para interpretar cuando se alejan de la parte central, los valores de distribución de datos.
    p.mb-4 En estos parámetros son importantes los siguientes términos:

    .row.justify-content-center.align-items-center.mb-4
      .col-lg-10
        .row.justify-content-center.align-items-center
          .col-sm-6.col-lg-4.mb-4.mb-xl-0.hh1
            .tarjeta.tarjeta-flip.color-secundario
              .tarjeta-flip__contenedor
                .tarjeta-flip__img.fnd-5(:style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img-10.svg')})`}")
                .tarjeta-flip__contenido.p-4.fnd-5
                  h4.text-center Rango o recorrido
                  p.text-center Es la diferencia entre el dato mayor y el dato menor de los datos de una distribución numérica.                  
          .col-sm-6.col-lg-4.mb-4.mb-xl-0.hh1
            .tarjeta.tarjeta-flip.color-secundario(@mouseover="indicadorTarjetaFlip = false")
              .indicador--hover(v-if="indicadorTarjetaFlip")
              .tarjeta-flip__contenedor
                .tarjeta-flip__img.fnd-5(:style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img-11.svg')})`}")
                .tarjeta-flip__contenido.p-4.fnd-5
                  h4.text-center Desviación
                  p.text-center La desviación media es la media aritmética de los valores absolutos de las desviaciones respecto a la misma media. 
          .col-sm-6.col-lg-4.mb-4.mb-xl-0.hh1
            .tarjeta.tarjeta-flip.color-secundario
              .tarjeta-flip__contenedor
                .tarjeta-flip__img(:style="{'background-image': `url(${require('@/assets/curso/temas/tema2/img-12.svg')})`}")
                .tarjeta-flip__contenido.p-4.fnd-5
                  h4.text-center Varianza
                  p.text-center Es una medida que representa la variabilidad de una serie de datos respecto a su media.                    

    p Para ampliar la información, lo invitamos a ver el video #[b Medidas de dispersión – datos no agrupados], el cual se encuentra en el material complementario.


</template>

<script>
export default {
  name: 'Tema2',
  data: () => ({
    // variables de vue
    indicadorTarjetaFlip: true,
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
