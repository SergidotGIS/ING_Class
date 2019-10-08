# Necesitaría saber la class

* Cada una de las coropletas
```
Coropletas: --> div [id="choroplets-hoods" class="custom-left-scrollbar filters-scroll-container"]

     VIVIENDA --> span [class="leftMargin itemsStyle"]
     div [class="grouped fields"]
          - Alquiler vs Compra: div [class="ui radio checkbox ING-orange-radio"] --> input [id="alquilerVScompra" type="radio" name="choroplets-radio" data-memory="Alquiler vs. compra" class="hidden"]
          - Precio de alquiler: div [class="ui radio checkbox ING-orange-radio"] --> input [id="precioMedioViviendaAlquiler" type="radio" name="choroplets-radio" data memory="Precio de alquiler" class="hidden"]
          - Precio de venta: div [class="ui radio checkbox ING-orange-radio"] --> input [id="precioMedioViviendaVenta" type="radio" name="choroplets-radio" data-memory="Precio de venta" class="hidden"]
          - Precio m2 de alquiler: div [class="ui radio checkbox ING-orange-radio"] --> input [id="precioUnitarioViviendaAlquiler" type="radio" name="choroplets-radio" data-memory="Precio m2 de alquiler" class="hidden"]
          - Precio m2 de venta: div [class="ui radio checkbox ING-orange-radio"] --> input [id="precioUnitarioViviendaVenta" type="radio" name="choroplets-radio" data-memory="Precio m2 de venta" class="hidden"]
          - Antigüedad de las viviendas: div [class="ui radio checkbox ING-orange-radio"] --> input [id="añoEdificacionVivienda" type="radio" name="choroplets-radio" data-memory="Antigüedad de las viviendas" class="hidden"]
          - Tipo de vivienda: div [class="ui radio checkbox ING-orange-radio hidden"] --> input [id="viviendaTipo" type="radio" name="choroplets-radio" data-memory="Tipo de vivienda" class="hidden"]
          - Tamaño de vivienda: div [class="ui radio checkbox ING-orange-radio hidden"] --> input [id="viviendaTamaño" type="radio" name="choroplets-radio" data-memory="Tamaño medio de vivienda (m2)" class="hidden"]

     SERVICIOS --> span [class="leftMargin itemsStyle"]
     div [class="grouped fields"] --> div [class="field"]
          - Acceso a guarderias: div [class="ui radio checkbox ING-orange-radio"] --> input [id="guarderias" type="radio" name="choroplets-radio" data-memory="Acceso a guarderías" class="hidden"]
          - Acceso a parques: div [class="ui radio checkbox ING-orange-radio"] --> input [id="parques" type="radio" name="choroplets-radio" data-memory="Acceso a parques" class="hidden"]
          - Acceso a colegios: div [class="ui radio checkbox ING-orange-radio"] --> input [id="colegios" type="radio" name="choroplets-radio" data-memory="Acceso a colegios" class="hidden"]
          - Acceso a hospitales: div [class="ui radio checkbox ING-orange-radio"] --> input [id="hospitales" type="radio" name="choroplets-radio" data-memory="Acceso a hospitales" class="hidden"]
          - Acceso a cultura y ocio: div [class="ui radio checkbox ING-orange-radio"] --> input [id="culturaOcio" type="radio" name="choroplets-radio" data-memory="Acceso a cultura y ocio" class="hidden"]
          - Acceso a mercados municipales: div [class="ui radio checkbox ING-orange-radio"] --> input [id="mercadosMunicipales" type="radio" name="choroplets-radio" data-memory="Acceso a mercados municipales" class="hidden"]
          - Acceso a tiendas de conveniencia: div [class="ui radio checkbox ING-orange-radio"] --> input [id="alimentos" type="radio" name="choroplets-radio" data-memory="Acceso a alimentos básicos" class="hidden"]
          - Acceso a farmacias: div [class="ui radio checkbox ING-orange-radio"] --> input [id="farmacias" type="radio" name="choroplets-radio" data-memory="Acceso a farmacias" class="hidden"]
          - Transporte público: div [class="ui radio checkbox ING-orange-radio"] --> input [id="transportePublico" type="radio" name="choroplets-radio" data-memory="Transporte público" class="hidden"]

     SOCIODEMOGRÁFICOS
     div [class="grouped fields"]
          - Renta bruta por hogar: div [class="field"] --> div [class="ui radio checkbox ING-orange-radio"] --> input [id="poblacionRenta" type="radio" name="choroplets-radio" data-memory="Renta bruta por hogar" class="hidden"]
          - Casados: div [class="field"] --> div [class="ui radio checkbox ING-orange-radio"] --> input [id="estadoCivilCasados" type="radio" name="choroplets-radio" data-memory="Casados" class="hidden"]
          - Solteros: div [class="field"] --> div [class="ui radio checkbox ING-orange-radio"] --> input [id="estadoCivilSingles" type="radio" name="choroplets-radio" data-memory="Solteros" class="hidden"]
          - Empadronados: div [class="field"] --> div [class="ui radio checkbox ING-orange-radio"] --> input [id="poblacionTotal" type="radio" name="choroplets-radio" data-memory="Empadronados" class="hidden"]
          - Densidad de población: div [class="field"] --> div [class="ui radio checkbox ING-orange-radio"] --> input [id="densidadPoblacion" type="radio" name="choroplets-radio" data-memory="Densidad de población (Total/km2)" class="hidden"]
          - Hombres: div [class="field"] --> div [class="ui radio checkbox ING-orange-radio"] --> input [id="sexoHombre" type="radio" name="choroplets-radio" data-memory="Hombres" class="hidden"]
          - Mujeres: div [class="field"] --> div [class="ui radio checkbox ING-orange-radio"] --> input [id="sexoMujer" type="radio" name="choroplets-radio" data-memory="Mujeres" class="hidden"]
          - Población por edades: div [class="field"] --> div [class="ui radio checkbox ING-orange-radio"] --> input [id="edad" type="radio" name="choroplets-radio" data-memory="Población por edades" class="hidden"]

```

* Cada uno de los filtros y cada una de las opciones de los filtros
```
Filtros: --> div [id="filters-hoods" class="custom-left-scrollbar filters-scroll-container"]

     MI CASA --> p [class="leftMargin titleStyle left"]

          Presupuesto --> span [class="leftMargin itemsStyle tiene-html"]
          form --> [class="--flex-row"]
               - Alquiler: label [class="container-custom"]
                    input [id="alquiler-node" type="radio" name="regimen-checkbox" value="alq_o_pm"]
                    span [class="checkmark-custom"]
                         - Slider Alquiler: div [id="price-slider-compra-container"]
                                             div [class="slider-track"]
                                             div [class="slider-handle min-slider-handle round"]
                                             div [class="slider-handle max-slider-handle round"]
                                             span [class="range-slider-span pull-left"]
                                             span [class="range-slider-span pull-right"]
               - Compra: label [class="container-custom"]
                    input [id="compra-node" type="radio" name="regimen-checkbox" value="cv_o_pm"]
                    span [class="checkmark-custom"]
                         - Slider Compra: div [id="price-slider-compra-container"]
                                             div [class="slider-track"]
                                             div [class="slider-handle min-slider-handle round"]
                                             div [class="slider-handle max-slider-handle round"]
                                             span [class="range-slider-span pull-left"]
                                             span [class="range-slider-span pull-right"]

          Estilo de casas --> span [class="leftMargin itemsStyle"]
               - Antiguas y con historia: div [class="ui checkbox ING-orange"] --> input [id="antiguas-historia-node" type="checkbox" value="antiguas-historia" name="estilo-checkbox" class="hidden"]
               - No tan antiguas: div [class="ui checkbox ING-orange"] --> input [id="no-tan-antiguas-node" type="checkbox" value="no-tan-antiguas" name="estilo-checkbox" class="hidden"]
               - Nuevas y modernas: div [class="ui checkbox ING-orange"] --> input [id="nuevas-modernas-node" type="checkbox" value="nuevas-modernas" name="estilo-checkbox" class="hidden"]

          Tamaño medio(m2) --> span [class="leftMargin itemsStyle tiene-html"]
               - < 60 m2: div [class="ui checkbox ING-orange"] --> input [id="minus-60-node" type="checkbox" value="_60" name="size-checkbox" class="hidden"]
               - 60 - 90 m2: div [class="ui checkbox ING-orange"] --> input [id="e60-90-node" type="checkbox" value="60_90" name="size-checkbox" class="hidden"]
               - > 90 m2: div [class="ui checkbox ING-orange"] --> input [id="plus-90-node" type="checkbox" value="90_" name="size-checkbox" class="hidden"]

          Distancia a un punto --> p [class="leftMargin itemsStyle tiene-html"]
          form --> [class="--flex-row"]
               - Andando: label [class="container-custom"]
                    input [id="andando-node" type="radio" name="distancia-checkbox" value="andando"]
                    span [class="checkmark-custom"]
                         - Slider Andando: div [id="time-slider-container"]
                                             div [class="slider slider-horizontal"]
               - En coche: label [class="container-custom"]
                    input [id="div [" type="radio" name="distancia-checkbox" value="en-coche"]
                    span [class="checkmark-custom"]
                         - Slider Andando: div [id="time-slider-container"]
                                             div [class="slider slider-horizontal"]

     MIS VECINOS --> p [class="leftMargin titleStyle left"]

          Edad media (años) --> span [class="leftMargin itemsStyle tiene-html"]
               - < 25: div [class="ui checkbox ING-orange"] --> input [id="minus-25-age-node" type="checkbox" value="_25age" name="age-checkbox" class="hidden"]
               - 25 - 45: div [class="ui checkbox ING-orange"] --> input [id="e25-45-age-node" type="checkbox" value="25_45age" name="age-checkbox" class="hidden"]
               - 45 - 65: div [class="ui checkbox ING-orange"] --> input [id="e40-65-age-node" type="checkbox" value="45_65age" name="age-checkbox" class="hidden"]
               - > 65: div [class="ui checkbox ING-orange"] --> input [id="plus-65-age-node" type="checkbox" value="65age" name="age-checkbox" class="hidden"]

          Tipo de familia --> span [class="leftMargin itemsStyle tiene-html"]
               - Jubilados: div [class="ui checkbox ING-orange"] --> input [id="parejas-mayores-node" type="checkbox" value="parejas-mayores" name="familia-checkbox" class="hidden"]
               - Familiar con hijos: div [class="ui checkbox ING-orange"] --> input [id="familias-con-hijos-node" type="checkbox" value="familias-con-hijos" name="familia-checkbox" class="hidden"]
               - Pisos compartidos: div [class="ui checkbox ING-orange"] --> input [id="pisos-compartidos-node" type="checkbox" value="pisos-compartidos" name="familia-checkbox" class="hidden"]
               - Solteros: div [class="ui checkbox ING-orange"] --> input [id="singles-node" type="checkbox" value="singles" name="familia-checkbox" class="hidden"]

     MI BARRIO --> p [class="leftMargin titleStyle left"]

          Ambiente --> span [class="leftMargin itemsStyle tiene-html"]
               - Tranquilo: div [class="ui checkbox ING-orange"] --> input [id="tranquilo-node" type="checkbox" value="tranquilo" name="ambiente-checkbox" class="hidden"]
               - Animado: div [class="ui checkbox ING-orange"] --> input [id="animado-node" type="checkbox" value="animado" name="ambiente-checkbox" class="hidden"]

          Servicios --> span [class="leftMargin itemsStyle tiene-html"]
               - Colegios: div [class="ui checkbox ING-orange"] --> input [id="enseñanza-infantil-node" type="checkbox" name="servicios-checkbox" class="hidden"]
               - Universidades: div [class="ui checkbox ING-orange"] --> input [id="enseñanza-universitaria-node" type="checkbox" name="servicios-checkbox" class="hidden"]
               - Cultura y ocio: div [class="ui checkbox ING-orange"] --> input [id="cultura-ocio-node" type="checkbox" name="servicios-checkbox" class="hidden"]
               - Mercados: div [class="ui checkbox ING-orange"] --> input [id="mercados-node" type="checkbox" name="servicios-checkbox" class="hidden"]
               - Comercios: div [class="ui checkbox ING-orange"] --> input [id="comercios-node" type="checkbox" name="servicios-checkbox" class="hidden"]
               - Transporte: div [class="ui checkbox ING-orange"] --> input [id="transporte-node" type="checkbox" name="servicios-checkbox" class="hidden"]
               - Centros deportivos: div [class="ui checkbox ING-orange"] --> input [id="centros-deportivos-node" type="checkbox" name="servicios-checkbox" class="hidden"]
               - Zonas verdes: div [class="ui checkbox ING-orange"] --> input [id="parques-node" type="checkbox" name="servicios-checkbox" class="hidden"]
```

* Cada una de las secciones de la ficha (vivienda, servicios, sociodemográficos)
```
FICHA BARRIO --> div [id="card-container-1test" class="main-matched-hood-body esee"]

Botón Vivienda: -->  a [id="home-tab-node-1" class="item" data-tab="home-tab"]
Botón Servicios: -->  a [id="services-tab-node-1" class="item" data-tab="services-tab"]
Botón Sociodemográficos: -->  a [id="sociodemo-tab-node-1" class="item" data-tab="sociodemo-tab"]

     SECCIÓN VIVIENDA --> div
          Precio medio: div [class"population-matched-title"]
                         div [style="display: flex !important;flex-direction: column !important;"]
                         h2 [class="leftMargin left first-card-title"]
               -Alquiler: table
               -Compra: table
          Alquiler VS Compra: div [style="display: flex !important; flex-direction: column !important;"]
                         h2 [class="leftMargin left first-card-title"]
               -Alquiler: Chart-canvas
               -Compra: Chart-canvas
          Antigüedad de las viviendas: div
                         h2 [class="leftMargin matched-title left"]
               - < 25 | 25 - 50 | > 50 años: Chart-canvas



     SECCIÓN SERVICIOS --> div
          Puntos de interés: h2 [class="leftMargin matched-title left"]
                              div [id="interest-points-container-1" style="margin-top: 3rem;"]
               - Diferentes puntos de interés: div [class="indicators-container"]
          Cajeros y puntos twyp: div --> div [style="display: flex !important;flex-direction: column !important;"]
                                   h2 [class="leftMargin matched-title left"]
                                   div [class="twyp-main-box"]



     SECCIÓN SOCIODEMOGRÁFICOS
          Renta bruta por hogar: div --> div [class="--flex-column"]
                                   h2 [class="leftMargin matched-title left"]
                                   p [id="income-indicator-node-1" class="huge-indicator"]
          Tipos de hogares: div --> div [class="--flex-column"]
                                   h2 [class="leftMargin matched-title left tooltip-msg tiene-tooltip"]
                                   as-category-widget [id="home-type-chart-1" class="home-type-category-widget hydrated"]
          Población Total: div --> div [class="--flex-column"]
                                   h2 [class="leftMargin matched-title left"]
                                   p [id="population-indicator-node-1" class="huge-indicator"]
          Densidad de población: div --> div [class="--flex-column"]
                                   h2 [class="leftMargin matched-title left"]
                                   p [id="density-indicator-node-1" class="huge-indicator"]
          Por estado civil: div --> div [style="display: flex !important; flex-direction: column !important;"]
                                   h2 [class="leftMargin matched-title left"]
                                   -Por estado civil: Chart-canvas
          Por edad: div --> div [class="--flex-column"]
                                   p [class="compare-matched-title"]
                                   div [class="--flex-row"]
          Por sexo: div [style="margin-bottom: 3rem;"] --> div [style="display: flex !important; flex-direction: column !important;"]
                                   h2 [class="leftMargin matched-title left"]
                                   div [style="margin:1rem;display:flex;flex-direction:column;"] --> - Por sexo: Chart-canvas
```

* Acceso a rrss
```
Botón Acceso RRSS: div [class="main-matched-hood-header-buttons"] --> div [class="--flex-row icons-mb-all"] --> img [id="share-hood-icon-1" src="img/latest/share-logo.png" style="margin: .35rem 1rem;"]
```

* Acceso a comparar
```
Botón Acceso Comparar: div [class="main-matched-hood-header-buttons"] --> div [class="--flex-row icons-mb-all"] --> div [class="compare-hood-icon-tooltip"] --> a [id="compare-hood-icon-tooltip"]
```

* Acceso a embeber
```
Botón Acceso Embeber: div [id="embed-widget-node"] --> i [class="embed-i embed-arrow-left"]
                                                       i [class="embed-i embed-arrow-right"]
```

* Acceso a Test
```
Botón Acceso Test: div [id="btn-test" class="btn-test-style tiene-tooltip tooltip-msg add-click"]
```

* Boton de salir del test
```
Botón Salir del Test: div [class="column"] --> div [id="center-tooltip" class="tiene-tooltip"] --> h5 [class="ing-orange"] --> img [id="btn-salir" class="img-salir right-fl"]
```

* Cada una de las preguntas del test
```
PREGUNTAS div [id="modal"]
     Preguntas Ciudad: div [id="panels"] --> form [class="ui form panel" id="panel0"]
     Preguntas Tu casa 1: div [id="panels"] --> form [class="ui form panel" id="panel1"] --> div [class="fila"]
     Preguntas Tu casa 2: div [id="panels"] --> form [class="ui form panel" id="panel2"]
     Preguntas Vecinos: div [id="panels"] --> form [class="ui form panel" id="panel3"]
     Preguntas Barrio: div [id="panels"] --> form [class="ui form panel" id="panel4"]
     Preguntas Barrio 2: div [id="panels"] --> form [class="ui form panel" id="panel5"] --> div [class="fila"]
     Preguntas Barrio 3: div [id="panels"] --> form [class="ui form panel" id="panel6"]
```

* Selector de ciudad en el panel de la izquierda
```
SELECTOR CIUDADES: div [id="citySelector-container" class="--flex-row"] --> as-dropdown [id="citySelector" class="hydrated"] --> div [class="as-dropdown"] --> button [class="as-dropdown__control as-body"]
```

* Los botones de la ayuda (entendido y hacer tour)
```
BOTÓN ENTENDIDO: div [class="popover tour-tour tour-tour-0 fade right in"] --> div [class="popover-navigation"] --> button [class="btn btn-sm btn-help"]

BOTÓN HACER TOUR: div [class="popover tour-tour tour-tour-0 fade right in"] --> div [class="popover-navigation"] --> div [id="btn-help" class="btn btn-sm btn-default add-click"]
```

* Cada uno de los rankings en la ficha de barrio
```
BOTÓN RANKING PRECIO MEDIO: div [class="--flex-row full-width m-left-70"] --> span [id="avg-price-indicator-ranking-1" class="ing-ranking pull-right"]

BOTÓN RANKING ALQUILER VS COMPRA: div [class="--flex-row full-width m-left-70"] --> span [id="rent-vs-purchase-indicator-ranking-1" class="ing-ranking pull-right"]

BOTÓN RANKING ANTIGÜEDAD DE LAS VIVIENDAS: div [class="--flex-row full-width m-left-70"] --> span [id="buildings-indicator-ranking-1" class="ing-ranking pull-right"]

BOTÓN RANKING CAJERS Y PUNTOS TWYP: div [class="--flex-row full-width m-left-70"] --> span [id="twyp-indicator-ranking-1" class="ing-ranking pull-right"]

BOTÓN RANKING RENTA BRUTA POR HOGAR: div [class="--flex-row full-width m-left-70"] --> span [id="income-indicator-ranking-1" class="ing-ranking pull-right"]

BOTÓN RANKING TIPOS DE HOGARES: div [class="--flex-row full-width m-left-70"] --> span [id="type-of-home-indicator-ranking-1" class="ing-ranking pull-right"]
BOTÓN RANKING POBLACIÓN: div [class="--flex-row full-width m-left-70"] --> span [id="population-indicator-ranking-1" class="ing-ranking pull-right"]

BOTÓN RANKING DENSIDAD DE POBLACIÓN: div [class="--flex-row full-width m-left-70"] --> span [id="density-indicator-ranking-1" class="ing-ranking pull-right"]
BOTÓN RANKING POR ESTADO CIVIL: div [class="--flex-row full-width m-left-70"] --> span [id="civil-status-chart-ranking-1" class="ing-ranking pull-right"]

BOTÓN RANKING POR EDAD: div [class="--flex-row full-width m-left-70"] --> span [id="pyramid-chart-ranking-1" class="ing-ranking pull-right"]

BOTÓN RANKING POR SEXO: div [class="--flex-row full-width m-left-70"] --> span [id="sex-indicator-ranking-1" class="ing-ranking pull-right"]
```

* El boton de "¿Cuanto te costaría vivir aqui?"
```
BOTÓN CALCULA TU HIPOTECA: -->  div [class="calcula-tu-hipoteca-button-container"] --> div [id="mortgage-button-container-1" class="mortgage-button-fixed"] --> button [id="calcula-tu-hipoteca-node-1" class="big ui button tooltip-msg"]
```
