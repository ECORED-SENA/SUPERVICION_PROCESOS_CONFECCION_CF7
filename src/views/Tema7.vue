<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 7
      h1 Mantenimiento y atención a problemas menores

    .row.mb-5
      .col-lg-7
        p Existen situaciones con las máquinas y herramientas, dentro de las plantas de confección, que no ameritan una asistencia de un personal muy técnico, cuyo tiempo de labor debe ser aprovechado de mejor manera. Estas situaciones menores pueden ser atendidas por otro personal dentro de la organización, incluso personal operativo. A veces se pierden tiempos de los equipos de producción, y cuando estos atienden el asunto se establece que la solución a dicho problema la puede resolver una persona que, aunque no tenga una formación técnica amplia, puede por medio de talleres o formación corta adquirir las competencias necesarias para resolver este tipo de problemas leves o menores.

        p Se entiende que cuando una máquina está parada y deja de producir, todo el presupuesto de producción, y por supuesto el de ventas, se afecta; en las empresas de confección el presupuesto destinado a la mano de obra para atender las averías de las máquinas es muy preciso, y el tiempo debe ser utilizado de la mejor manera. El personal operativo, con una instrucción adecuada de concentración, enfoque en el trabajo y mediante talleres de capacitación puede atender casos donde no sea necesaria la presencia de un técnico calificado. 
      .col-lg-5.d-flex
        figure.mb-5
          img(src='@/assets/curso/tema_7/img_1.png', alt='Texto que describa la imagen')

    .cajon.color-secundario.p-4.mb-5
      p Los casos más comunes que se presentan son: agujas mal colocadas o elegidas, mal enhebrado de la máquina, mal puesto el carretel en la bobina, tensiones mal calibradas e hilos mal puestos en el portaconos, entre otros

    p En el tema de mantenimiento, el personal operativo, tiene unas responsabilidades específicas, una de las cuales es atender el mantenimiento preventivo, como la lubricación y el aseo de las máquinas. Como en todo escenario laboral, usualmente suceden ciertos percances que podrían pensarse como situaciones problemáticas para llevar a cabo cualquier proceso o acción; y el área del mantenimiento de máquinas no es la excepción, puesto que en las plantas de confección comúnmente se presentan ciertos elementos que conllevan a una revisión para determinar la gravedad y solución de un problema. 

    p De esta forma, al conocer acciones esenciales, se hace referencia a los primeros auxilios para el mantenimiento de máquinas, lo que significa la acción seguida a la identificación del factor que está causando interferencia en la máquina, reconociendo si es de gran magnitud o simplemente requiere un ajuste, pequeño arreglo o cambio de algún componente. Entender cómo actuar en este tipo de casos donde no hay mayor necesidad de solicitar la ayuda del profesional en mecánica o ingeniería para arreglar las máquinas, permitirá optimizar tiempo de producción y evitar retrasos en los procesos productivos.

    p.mb-5 Para ello, se ha pensado en los problemas más comunes que pueden generarse y sus posibles soluciones, siempre y cuando no se presenten mayores dificultades para que el mismo operario pueda desenvolverse de la forma más adecuada ante la eventualidad.

    .row.justify-content-center
      .col-lg-10

        .bloque-texto-d.color-secundario.p-4
          .bloque-texto-d__texto.mb-2
            i.fas.fa-quote-left
            p.text-regular De acuerdo con Tabares (1990) en su cartilla Mantenimiento en la industria de la confección (problemas técnicos y soluciones) se evidencian posibles problemas mecánicos que pueden surgir con mayor frecuencia con las máquinas de confección, así como la solución sugerida. Estos se muestran en la siguiente tabla, donde se eligieron problemas menores para ser corregidos, puesto que otros de mayor magnitud no entran en la categoría de primeros auxilios en mantenimiento de máquinas de confección.
              i.fas.fa-quote-right

    
        

</template>

<script>
export default {
  name: 'Tema6',
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

<style lang="sass" scoped></style>
