<template lang="pug">
.curso-main-container.pb-3
  BannerInterno(icono="fas fa-sitemap" titulo="Síntesis")
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    p.mb-4 El siguiente mapa integra los criterios y especificidades de los conocimientos expuestos en el presente componente formativo.
    
    .row.justify-content-center
      .col-lg-10.mb-5
        figure
          img(src="@/assets/curso/temas/sintesis.svg", alt="A continuación, se presenta la síntesis del componente formativo: Etapas del procesamiento de datos y métodos estadísticos. Donde se encuentran la estadística, compuesta por su historia y evolución y conformada por las características, muestra, determinación de la muestra y población. Clasificación de datos compuesta por la validación de parámetros estadísticos, como los de centralización, dispersión y posición. Además, clasifica la información por medio de diagrama de tallo y hojas, y tabla de distribución de frecuencias. Tabulación, gráficas y análisis de datos compuesta por variables, tabla de frecuencias, tipos de gráficas y elementos determinantes para el análisis CAC. Mejora continua, evaluación e informes conformada por mecanismos para identificación de causa raíz.")
      .col-auto
        a.anexo.mb-4(:href="obtenerLink('/downloads/Sintesis.pdf')" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Síntesis

</template>

<script>
export default {
  name: 'Sintesis',
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
