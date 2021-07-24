<template lang="pug">
section
  .banner-principal.mb-5
    .container.tarjeta.p-4.p-sm-5(
      :style="{'background-image': `url(${require('@/assets/curso/fondo-banner-principal.png')})`}"
    )
      .row.justify-content-around.align-items-center
        .col-lg-7.col-xxl-6.banner-principal__info
          .banner-principal__programa
            .h1.mb-0 Tecnología en regencia de farmacia
          
          .h2 Información del programa
          .banner-principal__datos
            ul
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Nombre del programa: 
                p.banner-principal__datos__item__texto Tecnología en regencia de farmacia
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Código: 
                p.banner-principal__datos__item__texto 331502
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Total: 
                p.banner-principal__datos__item__texto 3984 Horas
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Duración: 
                p.banner-principal__datos__item__texto 27 meses
              li.mb-3.banner-principal__datos__item
                p.h4.mb-0.me-3.banner-principal__datos__item__titulo Modalidad: 
                p.banner-principal__datos__item__texto A distancia
              

        .d-none.d-lg-block.col-lg-5
          //- img(src="@/assets/curso/banner-princiapal.svg")
          .video
            | <iframe data-v-1f9e4816="" width="560" height="315" src="https://www.youtube.com/embed/_6dym1GLsfg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen="allowfullscreen"></iframe>
           

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 1. Presentación

    p.mb-0 Bienvenido a la Tecnología en regencia de farmacia, modalidad a distancia. Este es un programa con una duración de 27 meses, en los cuales usted desarrollará competencias que le permitirán gestionar y desempeñarse en diversos aspectos relacionados con los medicamentos y dispositivos médicos referentes a su selección, adquisición, recepción, almacenamiento, dispensación y distribución, al igual que en la fabricación de medicamentos magistrales no estériles de uso tópico. 
      br
      br
      | Tendrá los conocimientos y destrezas para implementar propuestas de políticas y acciones de promoción, prevención del uso adecuado de medicamentos y dispositivos médicos e intervención del sector farmacéutico, dirigidas a la comunidad.
      br
      br
      | El programa ha sido creado con el ánimo de formar talento humano cualificado, competente e integral para el manejo de productos farmacéuticos y, con ello, aportar a las metas y estrategias de la Política Farmacéutica Nacional en el marco de las directrices internacionales relacionadas con la implementación de la garantía de la calidad, accesibilidad, eficiencia y planes de mejora continua en el servicio farmacéutico, en beneficio de los usuarios.
      br
      br
      | #[strong Le deseamos éxitos en su proceso de aprendizaje.]


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 2. Justificación<br>del programa

    p.mb-0 El programa Tecnólogo en regencia de farmacia modalidad a distancia se creó para brindar al sector productivo farmacéutico la posibilidad de incorporar personal con altas calidades laborales y profesionales que contribuyan al desarrollo económico, social y tecnológico de su entorno y del país; asimismo, ofrecer a los aprendices formación en las tecnologías de servicios a la salud.  En todo el país, se cuenta con potencial productivo en farmacia droguería de primer nivel, droguerías, agencias de especialidades farmacéuticas, depósitos de drogas, y su fortalecimiento y crecimiento socioeconómico, tanto a nivel regional como nacional, dependen en gran medida de un recurso humano cualificado y calificado, capaz de responder integralmente a la dinámica del sector. 
      br
      br
      | El SENA es una institución educativa que ofrece el programa con todos los elementos de formación profesional integral, sociales, tecnológicos y culturales, metodologías de aprendizaje innovadoras, acceso a tecnologías de última generación; estructurado sobre métodos más que contenidos, lo que potencia la formación de ciudadanos librepensadores, con capacidad crítica, solidaria y emprendedora. Cuenta con líneas de trabajo en la formación por proyectos, que generan expectativas para dar solución a necesidades actuales del sector farmacéutico, tales como gestión en la cadena de abastecimiento de productos naturales, medicamentos e insumos para la salud; con una fundamentación ética que les permite la capacidad de administrar un servicio farmacéutico dentro de los parámetros establecidos por la legislación vigente, incluyendo el manejo de personal. Además, cuenta con formación en investigación en las áreas de las ciencias farmacéuticas y administrativas que lo acreditan, haciéndolo pertinente y coherente con su misión, innovando permanentemente de acuerdo con las tendencias, cambios tecnológicos y necesidades del sector empresarial, impactando positivamente en la productividad, competitividad, equidad y desarrollo del país.


  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 3. Competencias<br>a desarrollar

    ul.lista-ul.px-3
      li
        i.lista-ul__vineta
        | Orientar personas según normatividad de salud.
      li
        i.lista-ul__vineta
        | Orientar investigación formativa según referentes técnicos.
      li
        i.lista-ul__vineta
        | Generar hábitos saludables de vida mediante la aplicación de programas de actividad física en los contextos productivos y sociales.
      li
        i.lista-ul__vineta
        | Razonar cuantitativamente frente a situaciones susceptibles de ser abordadas de manera matemática en contextos laborales, sociales y personales.
      li
        i.lista-ul__vineta
        | Utilizar herramientas informáticas de acuerdo con las necesidades de manejo de información.
      li
        i.lista-ul__vineta
        | Asistir personas según protocolos de primer respondiente y normativa de salud.
      li
        i.lista-ul__vineta
        | Seleccionar proveedores de acuerdo con políticas de aprovisionamiento y normativa técnica.
      li
        i.lista-ul__vineta
        | Recibir la mercancía según procedimientos técnicos.
      li
        i.lista-ul__vineta
        | Almacenar los productos según técnicas de almacenamiento y normativa.
      li
        i.lista-ul__vineta
        | Controlar los inventarios según indicadores y métodos.
      li
        i.lista-ul__vineta
        | Desarrollar procesos de comunicación eficaces y efectivos, teniendo en cuenta situaciones de orden social, personal y productivo.
      li
        i.lista-ul__vineta
        | Aplicación de conocimientos de las ciencias naturales (Química) de acuerdo con situaciones del contexto productivo y social.
      li
        i.lista-ul__vineta
        | Interactuar en lengua inglesa de forma oral y escrita dentro de los contextos sociales y laborales según los criterios establecidos por el Marco Común Europeo de Referencia para las Lenguas.
      li
        i.lista-ul__vineta
        | Gestionar procesos propios de la cultura emprendedora y empresarial de acuerdo con el perfil personal y los requerimientos de los contextos productivo y social.
      li
        i.lista-ul__vineta
        | Aplicar prácticas de protección ambiental, seguridad y salud en el trabajo de acuerdo con las políticas organizacionales y la normatividad vigente.
      li
        i.lista-ul__vineta
        | Enrique Low Murtra-Interactuar en el contexto productivo y social de acuerdo con principios éticos para la construcción de una cultura de paz.
      li
        i.lista-ul__vineta
        | Resultado de aprendizaje de la inducción.
      li
        i.lista-ul__vineta
        | Preparar productos farmacéuticos magistrales tópicos según prescripción médica y normativa de salud.
      li
        i.lista-ul__vineta
        | Ejercer derechos fundamentales del trabajo en el marco de la Constitución Política y los convenios internacionales. 
      li
        i.lista-ul__vineta
        | Entregar productos farmacéuticos según delegación y normativa de salud.
      li
        i.lista-ul__vineta
        | Administrar medicamentos vía intramuscular de acuerdo con prescripción médica y normativa de salud.
      li
        i.lista-ul__vineta
        | Lanzar la promoción comercial según objetivos y herramientas promocionales.



  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 4. Perfil<br>de ingreso

    ul.lista-ul.px-3
      li.mb-0
        i.lista-ul__vineta
        p
          b Nivel académico: 
          b-none media técnica
      li.mb-0
        i.lista-ul__vineta
        p
          b Curso: 
          b-none 11
      li.mb-0
        i.lista-ul__vineta
        p
          b Certificación académica 
      li.mb-0
        i.lista-ul__vineta
        p
          b Edad mínima definida en la ley:
          b-none  16 años
      li.mb-0
        i.lista-ul__vineta
        p
          b Presentar resultado de la prueba o examen de Estado de la educación media
  

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 5. Perfil<br>de egreso

    p Diseñar, documentar e implementar procesos básicos y especiales del servicio farmacéutico, según nivel de competencia y normatividad legal vigente.

  .container.tarjeta.tarjeta__template--azul-claro.p-4.p-md-5.mb-5(data-aos="fade-up")
    .titulo__template--a.mb-4
      span.h4 6. Estrategia<br>metodológica

    p El programa de Regencia de farmacia a distancia desarrolla sus actividades de formación en coherencia con la estrategia metodológica SENA, la cual está centrada en la construcción de autonomía para garantizar la calidad de la formación y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportada en la utilización de las tecnologías de la información y la comunicación, integradas en ambientes abiertos y pluritecnológicos, que en todo caso recrean el contexto productivo y vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. 
      br
      br
      | El programa lleva a cabo la mediación pedagógica dentro del proceso formativo articulando la planeación pedagógica con el proyecto, el cual es la principal estrategia que lleva a poner en contexto el aprendizaje. Se plantea que el aprendiz, a través de la mediación del instructor, desarrolle una propuesta activa en los ambientes de aprendizaje y dedique espacios de desarrollo autónomo a través de la mediación tecnológica de las plataformas Territorium, Sena Sofia plus y otras herramientas tecnológicas.
      br
      br
      | Centrada en la construcción de autonomía para garantizar la calidad de la formación en el marco de la formación por competencias, el aprendizaje por proyectos y el uso de técnicas didácticas activas que estimulan el pensamiento para la resolución de problemas simulados y reales; soportada en el utilización de las tecnologías de la información y la comunicación, integradas en ambientes virtuales de aprendizaje que vinculan al aprendiz con la realidad cotidiana y el desarrollo de las competencias. Igualmente, debe estimular de manera permanente la autocrítica y la reflexión del aprendiz sobre el quehacer y los resultados de aprendizaje que logra a través de la vinculación activa de las cuatro fuentes de información para la construcción de conocimiento: 

    ul.lista-ul.px-3
      li
        i.lista-ul__vineta
        | El instructor - Tutor
      li
        i.lista-ul__vineta
        | El entorno
      li
        i.lista-ul__vineta
        | las TIC
      li
        i.lista-ul__vineta
        | El trabajo colaborativo
  

          

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
