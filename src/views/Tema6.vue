<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 6
      h1 Guías y accesorios para la confección

    p Son elementos que se le adhieren, adaptan o incorporan a las máquinas como complemento para que aumenten su capacidad de hacer operaciones adicionales a las que era capaz de hacer en su diseño inicial, lo anterior, en muchos casos, ahorra la compra de otra máquina.

    p.mb-5 La guía por naturaleza que se utiliza es el pie prensatelas cuya forma, al hacer contacto con la tela, ayuda a hacer costuras rectas y a la distancia solicitada. 
    
      
    .cajon.color-primario.p-4.mb-5
      p 
        strong Como beneficios de utilización de guías se tienen los siguientes:
      .row.justify-content-center
        .col-lg-7
          ul.lista-ul.color1
            li
              i.fas.fa-atom
              span.c1 Manualmente no se logra la misma simetría y rectitud que se logra con las guías, por ese motivo en términos de calidad se cumplen mejor las expectativas de costura.
            li
              i.fas.fa-atom
              span.c1 Su costo es bajo, por lo tanto, ayuda a rebajar costos en la empresa.
            li
              i.fas.fa-atom
              span.c1 Las operaciones se realizan más rápido por ser la guía la que sostiene y conduce el tejido.
            li
              i.fas.fa-atom
              span.c1 Su instalación no es complicada, o sea que cualquiera lo puede hacer, y habitualmente están sujetas por tornillos.
            li
              i.fas.fa-atom
              span.c1 Ayudan a cumplir exigencias de diseño.
            li
              i.fas.fa-atom
              span.c1 Sirven para alimentar tejido y a que se unan dos piezas, también son excelentes para hacer dobladillos.
            li
              i.fas.fa-atom
              span.c1 El trabajo se vuelve más sencillo y produce menos fatiga, en beneficio del trabajador.
          
        .col-lg-4
          figure
            img.img-a(src='@/assets/curso/tema_6/img_1.png', alt='Texto que describa la imagen')
      
    p.text-center.mb-5 
      strong A continuación, se pueden observar las guías más usadas.

    .row.justify-content-center
      .col-lg-8
        p.BorTit #[strong Figura 26] #[br]Guías
        .row.justify-content-center
          .col-lg-3
            figure.mb-3
              img.img-a(src='@/assets/curso/tema_6/img_2.png', alt='Texto que describa la imagen')
            h5.text-center Guía trébol
          .col-lg-3
            figure.mb-3
              img.img-a(src='@/assets/curso/tema_6/img_3.png', alt='Texto que describa la imagen')
            h5.text-center Guía en forma de T
          .col-lg-3
            figure.mb-3
              img.img-a(src='@/assets/curso/tema_6/img_4.png', alt='Texto que describa la imagen')
            h5.text-center  Guía de rodillo
          .col-lg-3
            figure.mb-3
              img.img-a(src='@/assets/curso/tema_6/img_5.png', alt='Texto que describa la imagen')
            h5.text-center Guía de tope para fileteadora
        .row.justify-content-center
          .col-lg-3
            figure.mb-3
              img.img-a(src='@/assets/curso/tema_6/img_6.png', alt='Texto que describa la imagen')
            h5.text-center Dobladillador sencillo
          .col-lg-3
            figure.mb-3
              img.img-a(src='@/assets/curso/tema_6/img_7.png', alt='Texto que describa la imagen')
            h5.text-center Guía tipo avión
          .col-lg-3
            figure.mb-3
              img.img-a(src='@/assets/curso/tema_6/img_8.png', alt='Texto que describa la imagen')
            h5.text-center Guía tubular
        
        

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
