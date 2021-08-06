<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Tecnología en Gestión Agroempresarial
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Tecnología en Gestión Agroempresarial
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 723179
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Total Horas: 
                p.banner-principal__datos__item__texto 3689 horas
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Duración:  
                p.banner-principal__datos__item__texto 27 meses
              li.mb-3.banner-principal__datos__item
                p.h6.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto virtual


        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/-0JXH6RMneo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p Bienvenidos al programa al #[b Tecnólogo en Gestión Agroempresarial], el cual está enfocado en la producción primaria de productos agropecuarios y se caracteriza por desarrollar procesos biológicos que llevan a que la producción agrícola y pecuaria acorde con factores climatológicos, tecnológicos y requerimientos del mercado, a través de estrategias de planificación, sostenibilidad y adaptabilidad, ayuden a solucionar la demanda en la producción de alimentos de excelente calidad y de producción limpia y por ello, sus egresados serán competentes para administrar y gestionar el proceso productivo y de mercadeo en la empresa agropecuaria en la economía colombiana.

      br
      br
      | Por lo anterior, a lo largo del programa de formación se desarrollarán actividades que permiten llevar a cabo el proyecto #[b Implementación de un modelo de gestión administrativa y productiva de la empresa agropecuaria mediante el uso de las tecnologías de la información para impulsar el crecimiento económico de los pequeños y medianos productores de la región], creando actividades que apuntan a este fin.

      br
      br
      | De igual manera, se desarrollarán contenidos que abordan diferentes temas necesarios para quienes deseen ser expertos en la producción primaria de productos agropecuarios con procesos de certificación.

      br
      br
      | ¡Ánimo! Le aseguramos que al terminar este programa estará en la capacidad de desarrollar soluciones agroempresariales de su región.



  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación del programa

    p El sector agropecuario en nuestro país, tiene una gran importancia y perspectiva positiva a nivel social y económico, esto debido al incremento en la demanda mundial de alimentos, ya que se espera que en 2050 la población global alcance los 9700 millones de habitantes; de otra parte, la incidencia del sector agropecuario en la economía nacional es relevante, lo cual se refleja en un mayor incremento en la variación porcentual del producto interno bruto con respecto a otros renglones de la economía.

      br
      br
      | Por este motivo, el programa “Tecnólogo en Gestión Agroempresarial” habilita al egresado por medio de una estrategia de formación por competencias para administrar y gestionar el proceso productivo y de mercadeo en la empresa agropecuaria, utilizando técnicas y estrategias de planeación, mercadeo, manejo contable y de personal, aplicando resultados de investigación y usando tecnologías de la información; adicionalmente, contará con habilidades sociales y trasversales al área de formación y productiva, con el fin último de optimizar la producción y productividad de empresas del sector, así como emprender en la creación de sistemas de explotación agroindustriales.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3.	Competencias a desarrollar
    .row.justify-content-center.align-items-center 
      .col-lg-11
        ul.lista-ul
          li
            i.lista-ul__vineta
            p Programar proyectos según especificaciones técnicas y métodos de planeación
          li
            i.lista-ul__vineta
            p Implementar programa de certificación según estándares y proceso productivo.
          li
            i.lista-ul__vineta
            p Coordinar actividades de acuerdo con estrategias de gestión y proceso administrativo.
          li
            i.lista-ul__vineta
            p Implementar acciones estratégicas de mercadeo de acuerdo con segmentos y escenarios del mercado.
          li
            i.lista-ul__vineta
            p Dirigir el talento humano de acuerdo con normativa.
          li
            i.lista-ul__vineta
            p Contabilizar operaciones de acuerdo con las normas vigentes y políticas organizacionales.
          li
            i.lista-ul__vineta
            p Procesar datos de acuerdo con procedimiento técnico y metodología estadística.
          li
            i.lista-ul__vineta
            p Implementar condiciones bioseguras según sistema de producción pecuaria y normativa sanitaria.
          li
            i.lista-ul__vineta
            p Coordinar producción de especie pecuaria según objetivos de la empresa.
          li
            i.lista-ul__vineta
            p Controlar labores agrícolas según tipo de cultivo y normativa.
          li
            i.lista-ul__vineta
            p Acondicionar producto agrícola según manual técnico.
          li
            i.lista-ul__vineta
            p Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
          li
            i.lista-ul__vineta
            p Aplicación de conocimientos de las ciencias naturales de acuerdo con situaciones del contexto productivo y social.
          li
            i.lista-ul__vineta
            p Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
          li
            i.lista-ul__vineta
            p Utilizar herramientas informáticas de acuerdo con necesidades de manejo de información.
          li
            i.lista-ul__vineta
            p Interactuar en lengua inglesa de forma oral y escrita dentro de contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de referencia para las lenguas.
          li
            i.lista-ul__vineta
            p Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
          li
            i.lista-ul__vineta
            p Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.
          li
            i.lista-ul__vineta
            p Enrique Low Murtra- Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
          li
            i.lista-ul__vineta
            p Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
          li
            i.lista-ul__vineta
            p Orientar investigación formativa según referentes técnicos.
          li
            i.lista-ul__vineta
            p Ejercer los derechos fundamentales del trabajo de acuerdo al reconocimiento de la dignidad.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil de ingreso
    .row.justify-content-center.align-items-center 
      .col-lg-11
        ul.lista-ul
          li
            i.lista-ul__vineta
            p #[b Nivel Académico:] Media Académica
          li
            i.lista-ul__vineta
            p #[b Curso:] Undécimo. 
          li
            i.lista-ul__vineta
            p #[b Formación para el Trabajo y el Desarrollo Humano:] No.
          li
            i.lista-ul__vineta
            p #[b Número de horas:] No.
          li
            i.lista-ul__vineta
            p #[b Requiere Certificación Académica:] Si.
          li
            i.lista-ul__vineta
            p #[b Requiere Experiencia Laboral:] No. 
          li
            i.lista-ul__vineta
            p #[b Edad Mínima Definida en la Ley: ] 15 años.
          li
            i.lista-ul__vineta
            p #[b Requisitos Adicionales:] Presentar resultado de la prueba o examen de estado de la educación media  
          li
            i.lista-ul__vineta
            p #[b Aspectos actitudinales, motivacionales y de interés:] Preferencia por el trabajo en ambientes rurales y productivos, con personal a cargo, crítico de la realidad en la que se desenvuelve, propositivo en la búsqueda de soluciones, asertivo en la comunicación y trabajo en equipo; organizado y veraz en el manejo de la información, hábil en el uso de herramientas tecnológicas. Interesado en temas ambientales y de producción de alimentos. 

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil de egreso
    p Este programa de formación creará personas interesadas en desarrollar competencias para la gestión de empresas agrícolas y pecuarias, con visión de generación de proyectos y certificación de procesos productivos. Por este motivo, es que se encaminará a los aprendices, emprendedores, empresarios, agremiaciones, organizaciones y por supuesto, al SENA.

      br
      br
      | Ocupaciones que podrá desempeñar el egresado (según la CNO Clasificación Nacional de Ocupaciones u ocupaciones emergentes identificadas por la Red y en trámite de inclusión a la CNO):

    .row.justify-content-center.align-items-center 
      .col-lg-11
        ul.lista-ul
          li
            i.lista-ul__vineta
            p Agricultores y Administradores Agropecuarios
          li
            i.lista-ul__vineta
            p Supervisores de Producción Agrícola


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia metodológica
    p Centrada en la construcción de autonomía del aprendizaje para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportadas en la utilización de las tecnologías de la información y la comunicación, integradas en ambientes virtuales de aprendizaje, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 

      br
      br
      | Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento:
    .row.justify-content-center.align-items-center 
      .col-lg-11
        ul.lista-ul
          li
            i.lista-ul__vineta
            p El instructor - Tutor
          li
            i.lista-ul__vineta
            p El entorno
          li
            i.lista-ul__vineta
            p Las TIC
          li
            i.lista-ul__vineta
            p El trabajo colaborativo


  //- Créditos
  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 Créditos

    
    .creditos
      div(
        v-for="(creditoKey, index) of Object.keys(creditosData)"
        :class="index != Object.keys(creditosData).length -1 ? 'mb-4' : ''" 
      )
        .creditos__titulo {{configTitulos[creditoKey]}}
        table
          tbody
            tr(
              v-for="(item, idx) of creditosData[creditoKey]" 
              :key="creditoKey+idx"
            )
              td.text-bold(colspan='2' v-html="renderText(item.nombre)")
              td(colspan='2' v-html="renderText(item.cargo)")
              td(colspan='3' v-html="renderText(item.centro)")

  Footer

</template>
<script>
export default {
  name: 'Inicio',
  data: () => ({
    configTitulos: {
      liderEquipo: 'ECOSISTEMA DE RECURSOS EDUCATIVOS DIGITALES',
      contenidoInstruccional: 'CONTENIDO INSTRUCCIONAL',
      desarrolloProducto:
        'DISEÑO Y DESARROLLO DE RECURSOS EDUCATIVOS DIGITALES',
      gestoresRepositorio: 'GESTORES DE REPOSITORIO',
    },
  }),
  computed: {
    creditosData() {
      return this.$config.creditos
    },
  },
  methods: {
    renderText(textObj) {
      let newText = ''
      if (Array.isArray(textObj)) {
        textObj.forEach((texto, index) => {
          newText += (index ? '<br/>' : '') + texto
        })
      } else {
        newText += textObj
      }
      return newText
    },
  },
}
</script>

<style lang="sass">
.creditos
  td, th
    border-color: $color-sistema-c
</style>
