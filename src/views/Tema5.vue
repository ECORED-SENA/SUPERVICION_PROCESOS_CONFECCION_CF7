<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5

    .titulo-principal
      .titulo-principal__numero
        span 5
      h1 Herramienta Total Productive Maintenance (TPM) - Mantenimiento Productivo Total

    .row.mb-5
      .col-lg-4
        figure
          img(src='@/assets/curso/tema_5/img_1.png', alt='Texto que describa la imagen')
      .col-lg-8
        p Es una herramienta de trabajo empresarial que se fundamenta en vincular el tema del equipo de máquinas y herramientas al plano productivo, relaciona de manera directa el impacto que genera en la producción los paros producidos por máquinas que no funcionan; estos paros significan el desaprovechamiento de la capacidad instalada, por lo que el TPM busca eliminar las causas que originan esos paros y esto se logra por medio de una gestión de mantenimiento efectiva; también se asocian algunos problemas de calidad que se pueden resolver manteniendo un equipo de maquinaria en excelentes condiciones; así mismo, se pueden evitar accidentes de trabajo con una buena administración de los programas de mantenimiento.

        p Según la filosofía TPM, mediante sistemas de mantenimiento preventivo eficaces se logra que las máquinas rara vez paren y no afecten las capacidades instaladas de las plantas de producción; si se cuentan con protocolos definidos para el plan de mantenimiento correctivo, la respuesta a un cese de actividad de máquina intempestivamente se podrá solucionar de manera rápida y con poca pérdida de tiempo. Cuando se implementa la filosofía TPM los accidentes de trabajo disminuyen debido a que se promueve orden, aseo y limpieza, lo mismo que la buena ubicación de herramientas y repuestos.
      
    .cajon.color-acento-botones.p-4.mb-5
      .row
        .col-lg-8
          P
            strong Esta filosofía se vincula de manera directa con las herramientas de #[i Lean Manufacturing] y para implementarlo se requiere:
      .row.justify-content-center
        .col-lg-6
          ul.lista-ul.color3
            li
              i.fas.fa-atom
              span.c1 Realizar un diagnóstico de la situación actual.
            li
              i.fas.fa-atom
              span.c1 Organizar un equipo con su respectivo líder.
            li
              i.fas.fa-atom
              span.c1 Recibir apoyo de la gerencia.
            li
              i.fas.fa-atom
              span.c1 Definir objetivos y metas.
            li
              i.fas.fa-atom
              span.c1 Generar una cultura y hábito de TPM.
            li
              i.fas.fa-atom
              span.c1 Comunicar el programa a todo el personal.
            li
              i.fas.fa-atom
              span.c1 Identificar puntos críticos para intervenir.
          
        .col-lg-4
          figure
            img(src='@/assets/curso/tema_5/img_2.png', alt='Texto que describa la imagen')
      
    p.text-center.mb-5 
      strong Según BSG Institute (2020), toda la implementación de TPM, se debe apoyar en 8 pilares para lograr los objetivos de eliminar o reducir las pérdidas.

    .row.justify-content-center
      .col-lg-8
        p.BorTit #[strong Figura 25] #[br]Los ocho pilares TPM
        figure.mb-5
          img(src='@/assets/curso/tema_5/img_3.png', alt='Texto que describa la imagen')
        p.mb-5 Se invita a profundizar a través del siguiente video sobre la metodología TPM para la realización de un mantenimiento productivo total:

        .row.justify-content-center
          .col-lg-8

            a.anexo.mb-4.mb-lg-0(href="https://www.youtube.com/watch?v=QdDPyNolNhk&ab_channel=GembaAcademyEspa%C3%B1ol" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-link.svg")
              .anexo__texto
                p #[strong Enlace web.] Gemba Academy Español. (2018). TPM Mantenimiento productivo total. 


</template>

<script>
export default {
  name: 'Tema5',
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
