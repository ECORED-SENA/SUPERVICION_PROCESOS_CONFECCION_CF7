<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 9
      h1 Puesta a punto de la máquina y el puesto de trabajo

    figure.mb-5
      img(src='@/assets/curso/tema_9/img_1.png', alt='Texto que describa la imagen')

    p La eficiencia de una planta de producción de confección se basa en el número de unidades manufacturadas relacionado con la cantidad de recursos utilizados. Pero para poder lograr lo anterior, se requiere de una buena programación de ellos, es decir, la operación o actividad que es, a la hora que es, en la máquina indicada y a la persona correcta, de esa manera, y con esa coordinación adecuada de recursos, se logran producir las unidades planeadas.

    p.mb-5 Todo lo anterior se puede lograr, pero si cuando el trabajo llegue con esa sincronización ocurre que la máquina no funciona, se podría malograr la programación anterior, entonces, aquí se nota la importancia del capítulo de este módulo y que complementa el plan de producción, que la máquina y el puesto de trabajo estén organizados de acuerdo con las especificaciones técnicas requeridas, tanto de la prenda como de la máquina.

    .cajon.color-primario.p-4.mb-5
      p 
        strong Poner a punto la máquina siguiendo especificaciones técnicas, tiene que ver con:
      .row.justify-content-center
        .col-lg-7
          ul.lista-ul.color1
            li
              i.fas.fa-atom
              span.c1 Calibrarla a las puntadas por pulgada solicitadas.
            li
              i.fas.fa-atom
              span.c1 Enhebrarla de la manera adecuada y con el hilo solicitado.
            li
              i.fas.fa-atom
              span.c1 El hilo que sea del calibre, el color, la composición y la posición solicitada.
            li
              i.fas.fa-atom
              span.c1 El hilo mediante los guía hilos debe ser tensionado de la manera requerida y de acuerdo con el tipo de tejido que se va a coser.
            li
              i.fas.fa-atom
              span.c1 El pie prensatelas debe cumplir la especificación solicitada para el margen de costura.
            li
              i.fas.fa-atom
              span.c1 La aguja debe ser coherente con el hilo y el tejido que se va a intervenir.
            li
              i.fas.fa-atom
              span.c1 Si se requieren accesorios adicionales deben estar incorporados a la máquina.
          
        .col-lg-4
          figure
            img(src='@/assets/curso/tema_9/img_2.png', alt='Texto que describa la imagen')

    p.mb-5 El puesto de trabajo debe estar limpio, las piezas a intervenir con costuras deben estar bien dispuestas, la instrucción de trabajo debe ser precisa, así mismo, la iluminación y altura de la máquina con respecto al operario debe ser la apropiada

    .row.justify-content-center
      .col-lg-8
        p.BorTit #[strong Figura 28] #[br]Imagen de una puesta a punto de una máquina de coser
        figure.mb-5
          img(src='@/assets/curso/tema_9/img_3.png', alt='Texto que describa la imagen')

        p.mb-5 Para concluir este tema, se invita a ver el siguiente video de la puesta a punto de una máquina de coser, en este caso de la marca Pfaff.

        .row.justify-content-center
          .col-lg-10
            a.anexo.mb-4.mb-lg-0.botton--bg2(href="https://www.youtube.com/watch?v=YNf0salcrlc&ab_channel=MecanicaConfeccion" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link-1.svg")
              .anexo__texto
                p #[strong Enlace web.] Mecánica de confección. (2018). Puesta a punto de las máquinas de coser. 







        

</template>

<script>
export default {
  name: 'Tema8',
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
