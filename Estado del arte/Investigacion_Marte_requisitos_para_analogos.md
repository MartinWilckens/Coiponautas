# Marte: condiciones de exploración y requisitos para análogos terrestres

**Proyecto:** NASA Space Apps Challenge 2026  
**Responsable de esta línea:** Matías  
**Fecha:** 14 de noviembre de 2026  
**Estado:** investigación inicial documentada; pendiente de revisión del equipo  
**Ubicación sugerida en GitHub:** `docs/investigacion/marte.md`

## 1. Propósito y alcance

Identificar las condiciones marcianas que una misión análoga necesita representar, para evaluar posteriormente sitios terrestres poco estudiados que puedan cubrir necesidades concretas de exploración.

Este documento organiza referencias científicas y propone líneas de análisis. No presenta un nuevo sitio terrestre validado, un ranking calculado ni resultados de procesamiento de datos. Las fuentes se consultaron durante la investigación previa a su elaboración; los productos científicos originales aún no se han descargado ni analizado.

La pregunta central es: **¿qué propiedades de un lugar terrestre permitirían estudiar o ensayar una tarea específica de exploración de Marte?**

## 2. Distinción inicial: Marte actual y Marte antiguo

Hay que separar las condiciones actuales necesarias para operar —atmósfera, temperatura, suelo, polvo y acceso al subsuelo— de los materiales y procesos que registran ambientes antiguos.

Una misión de perforación para obtener hielo necesita caracterizar el subsuelo actual. Una investigación de posibles biosignaturas puede centrarse en depósitos de antiguos lagos y su preservación. Ambas requieren analogías diferentes.

**Regla propuesta para el proyecto:** cada comparación debe identificar una región marciana, una tarea y la escala relevante. No asignar una única puntuación de parecido con todo Marte.

## 3. Regiones de referencia

| Región | Interés | Posible analogía terrestre | Tipo de evidencia y situación |
|---|---|---|---|
| Arcadia Planitia y sectores próximos de Amazonis | Hielo subsuperficial y potencial para futuras operaciones humanas | Suelo sobre hielo, terrenos periglaciales, excavación y muestreo | Observaciones orbitales y estudios de candidatos; no una base humana establecida |
| Jezero | Antiguo sistema fluvial y lacustre; habitabilidad y preservación | Depósitos deltaicos, sedimentos finos y alteración por agua | Observaciones orbitales y de Perseverance |
| Gale | Registro sedimentario y cambios ambientales | Secuencias sedimentarias, arcillas, sulfatos y alteración | Observaciones orbitales y de Curiosity |
| Oxia Planum | Materiales antiguos con arcillas y búsqueda de señales preservadas | Materiales alterados por agua, identificación mineralógica y muestreo | Caracterización orbital; sitio seleccionado para Rosalind Franklin |

Arcadia y Deuteronilus Mensae destacan en los estudios SWIM por reunir varias evidencias compatibles con materiales subsuperficiales ricos en hielo. Un trabajo de 2025 estudia tres candidatos en el límite Arcadia–Amazonis: AP-1, AP-8 y AP-9. La evidencia regional no establece condiciones idénticas en cada punto. [1, 2]

Jezero y Gale ofrecen evidencia desde la superficie sobre materiales y alteración por agua. Oxia dispone de un estudio de selección y contexto geológico: se describe como una región de bajo relieve de unos 200 km de extensión con unidades portadoras de arcillas. Esa extensión no es el tamaño de una futura área de comparación. [3, 4, 5]

## 4. Atmósfera y polvo

Como referencia general, Marte tiene una atmósfera dominada por CO₂ y una presión superficial aproximada de **6,35 mbar —635 Pa—**. La presión depende del lugar y del momento; no debe asignarse ese valor a todos los sitios. [6]

| Variable | Interés para la misión | Tratamiento propuesto |
|---|---|---|
| Presión y composición | Procesos físicos y funcionamiento de equipos | Registrar diferencias que el sitio terrestre no representa |
| Viento | Transporte de partículas y operaciones | Comparar el proceso relevante; una misma velocidad no garantiza el mismo efecto |
| Polvo atmosférico | Visibilidad, iluminación y exposición | Caracterizar cantidad, duración y variabilidad |
| Polvo depositado | Interacción con equipos y superficies | Investigar materiales y condiciones del ensayo |

**Fuentes locales de datos:** MEDA en Jezero y REMS en Gale. Los instrumentos incluyen observaciones de presión, temperatura del aire y del suelo, humedad y otras variables ambientales. Antes de usarlas hay que revisar disponibilidad, calibración y calidad de cada sensor y período. [7, 8]

La radiación óptica o ultravioleta registrada por una estación ambiental no debe tratarse automáticamente como una medición de toda la radiación ionizante relevante para una tripulación. Si esa dimensión se vuelve central, requerirá una línea específica de investigación.

## 5. Temperatura: comparar series locales

La caracterización térmica debe responder:

- ¿Qué temperatura tiene el suelo y cuál el aire?
- ¿Cómo evolucionan durante el día y entre estaciones?
- ¿Cuánto duran las condiciones relevantes para el ensayo?
- ¿A qué profundidad o altura se midió?
- ¿Qué observaciones faltan y qué correcciones requiere el instrumento?

REMS distingue temperaturas del suelo y del aire y ofrece productos procesados y documentación de calibración. [8]

### Análisis propuesto

1. Seleccionar un lugar y período documentados.
2. Separar las variables físicas antes de comparar.
3. Obtener mínimos, máximos, amplitudes y evolución temporal con controles de calidad.
4. Buscar observaciones terrestres compatibles en escala y muestreo.
5. Explicar las diferencias que afectan a la tarea.

No comparar una media anual terrestre con una observación aislada marciana. Tampoco interpretar dos observaciones satelitales diarias como un ciclo completo. Estas son reglas de trabajo propuestas, no análisis ya ejecutados.

## 6. Agua, hielo y sales

| Tema | Pregunta | Aplicación análoga |
|---|---|---|
| Hielo actual | ¿Dónde está, a qué profundidad y con qué evidencia? | Detección, perforación, extracción y conservación de muestras |
| Agua antigua | ¿Qué estructuras y materiales registran su presencia? | Interpretación geológica y selección de muestras |
| Sales | ¿Cuáles hay y qué procesos registran? | Identificación mineralógica, alteración y preservación |

### SWIM: hielo subsuperficial

El proyecto Subsurface Water Ice Mapping combina información de distintas misiones. La actualización presentada por NASA el **26 de octubre de 2023** incorporó imágenes de mayor resolución y cráteres recientes que exponen hielo, útiles para comprobar interpretaciones. Los mapas ayudan a localizar regiones potencialmente favorables para acceso al recurso. No determinan por sí solos cantidad y profundidad exactas en cada punto. [9]

### Phoenix: evidencia local

Phoenix confirmó hielo de agua en el subsuelo de su lugar de aterrizaje y detectó percloratos en 2008. Son resultados locales que sirven como referencia; no justifican asignar la misma composición a toda la superficie marciana. [10]

### Campos que debería contener nuestra ficha de hielo

- Tipo de evidencia: exposición observada, señal geofísica, morfología o modelo.
- Profundidad estimada y su incertidumbre, si están disponibles.
- Cobertura de suelo y propiedades documentadas.
- Escala y cobertura espacial del producto.
- Utilidad para una tarea específica.
- Medición que falta para confirmar la interpretación.

## 7. Geología: materiales, estructuras y procesos

| Elemento | Qué investigar |
|---|---|
| Materiales volcánicos | Composición, textura y alteración posterior |
| Arcillas | Tipo mineral, asociación y contexto de alteración |
| Sulfatos y otras sales | Composición y procesos compatibles con su formación |
| Canales y deltas | Geometría, depósitos y secuencia de eventos |
| Dunas y formas eólicas | Materiales, dimensiones y evidencia de actividad |
| Terrenos poligonales | Tamaño, distribución, contexto y mecanismos posibles |

**Pregunta útil para el proyecto:** ¿qué sector terrestre permite estudiar materiales y estructuras comparables a una unidad geológica concreta de Oxia, Jezero u otra región?

Una forma similar constituye una pista, pero no demuestra un origen compartido. La comparación debe combinar geometría, materiales y contexto cuando existan datos suficientes.

La topografía se estudiará a una escala compatible con la aplicación. Las conclusiones sobre relieve regional no certifican el paso de un vehículo sobre obstáculos pequeños.

## 8. Astrobiología

Conviene renombrar la rama del mapa como **“Habitabilidad, preservación y detección de biosignaturas”**.

| Concepto | Significado |
|---|---|
| Habitabilidad | Condiciones que podrían permitir vida |
| Preservación | Posibilidad de que sus señales sobrevivan |
| Detectabilidad | Posibilidad de medir esas señales con un instrumento |
| Origen biológico | Evidencia de que una señal procede de vida |

Los compuestos orgánicos no demuestran por sí solos un origen biológico. Un artículo de 2025 sobre la formación Bright Angel en Jezero describe asociaciones minerales, químicas y texturales como **biosignaturas potenciales**, que requieren investigación adicional para resolver su origen. [11, 12]

**Aplicación terrestre propuesta:** evaluar qué señales conserva un material y qué puede detectar un instrumento. El sitio no tiene que reproducir todas las condiciones marcianas para ser útil en esa pregunta, pero debe explicarse qué representa y qué no.

## 9. Datos que necesitamos localizar y comprobar

| Necesidad | Punto de partida | Comprobación pendiente |
|---|---|---|
| Ambiente local en Jezero | MEDA / PDS | Productos, intervalos, variables, calidad y formatos |
| Ambiente local en Gale | REMS / PDS | Descargar un período y separar aire, suelo y otros sensores |
| Hielo en latitudes medias | SWIM y estudios Arcadia–Amazonis | Resolución, significado del índice y evidencia por candidato |
| Geología de Oxia | Artículo de contexto y productos citados | Seleccionar unidad y área concreta |
| Relieve e imágenes planetarias | PDS y Orbital Data Explorer | Producto, escala, coordenadas y cobertura adecuada |
| Contrapartida terrestre | Earthdata y Copernicus | Disponibilidad de variables realmente comparables |

Los repositorios son puntos de acceso. La existencia de un portal no demuestra que todos los productos necesarios estén disponibles para todas las áreas.

## 10. Dos líneas iniciales propuestas

| Línea | Referencia | Necesidad que investigar |
|---|---|---|
| Hielo y operaciones | Arcadia–Amazonis | Terrenos terrestres para ensayar detección y acceso a hielo bajo suelo |
| Materiales y búsqueda de señales | Oxia o Jezero | Terrenos para muestreo e identificación en materiales alterados por agua |

**Propuesta:** estudiar primero Arcadia–Amazonis y Oxia como alternativas. No hay todavía una selección definitiva del equipo.

Para cada línea completar:

1. Objetivo de exploración.
2. Propiedades esenciales del terreno.
3. Evidencia y productos disponibles.
4. Características que un sitio terrestre tendría que representar.
5. Análogos terrestres ya utilizados y limitaciones documentadas.
6. Oportunidad concreta para un candidato menos estudiado.

La búsqueda de candidatos terrestres comenzará cuando exista una necesidad suficientemente definida. “Poco conocido” será una oportunidad de originalidad, no un sustituto de la idoneidad científica.

## 11. Entregable de la investigación de Marte

El resultado esperado es una **matriz de requisitos**, que permita al equipo evaluar candidatos terrestres y posteriormente construir los filtros del catálogo.

| Campo | Contenido esperado |
|---|---|
| Objetivo | Tarea científica u operacional |
| Región y unidad marciana | Referencia delimitada |
| Propiedad indispensable | Condición sin la cual el análogo no sirve |
| Variable observable | Qué se mediría y en qué unidad |
| Escala | Extensión y resolución necesarias |
| Fuente | Producto o publicación trazable |
| Evidencia | Medición, estimación o hipótesis |
| Limitación | Diferencia relevante entre Tierra y Marte |
| Verificación pendiente | Dato o ensayo necesario |

No asignar aún pesos numéricos universales. Primero deben definirse la tarea, los requisitos y los datos disponibles.

## 12. Rama de trabajo e integración

**Destino inicial recomendado: rama personal de Matías.** Este archivo documenta una línea de investigación, con propuestas aún pendientes de consenso.

Puede integrarse después a la rama general mediante revisión del equipo cuando:

- Las fuentes y afirmaciones principales hayan sido revisadas.
- El equipo entienda cuáles son resultados documentados y cuáles son propuestas.
- Las decisiones pendientes estén explícitas.
- Su estructura sea útil para las investigaciones de Luna y de sitios terrestres.

**No hace falta esperar a terminar toda la investigación para integrarlo.** Una versión inicial revisada puede vivir en la general y seguir ampliándose mediante aportes pequeños. Integrar el documento no implica que el equipo haya aprobado todas sus propuestas.

Este archivo se entrega para que el chat encargado del repositorio lo incorpore; no se ha realizado ninguna operación en GitHub.

## 13. Fuentes

1. **USGS / estudio SWIM (2021).** [Availability of subsurface water-ice resources in the northern mid-latitudes of Mars](https://www.usgs.gov/publications/availability-subsurface-water-ice-resources-northern-mid-latitudes-mars).
2. **Estudio Arcadia–Amazonis (2025).** [Geomorphological Evidence of Near-Surface Ice at Candidate Landing Sites in Northern Amazonis Planitia, Mars](https://doi.org/10.1029/2024JE008724).
3. **MIT, equipo investigador (2024).** [Rocks from Mars’ Jezero Crater contain signs of water](https://news.mit.edu/2024/study-mars-jezero-crater-rocks-contain-signs-of-water-0814).
4. **Rampe y colaboradores (2020).** [Mineralogy and geochemistry of sedimentary rocks and eolian sediments in Gale crater, Mars](https://ntrs.nasa.gov/api/citations/20205001822/downloads/Rampe_etal_2020_Geochemistry_Mineral_Geochem_in_Gale_after_6_yrs.pdf).
5. **Estudio de contexto de Oxia (2021).** [Oxia Planum: The Landing Site for the ExoMars Rosalind Franklin Rover Mission](https://doi.org/10.1089/ast.2019.2191).
6. **ESA.** [Meet Mars](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/Exploration/ExoMars/Meet_Mars/%28language%29/eng-GB). Valores generales, no series locales.
7. **NASA PDS.** [Descripción del instrumento MEDA](https://pds.nasa.gov/ds-view/pds/viewContext.jsp?identifier=urn%3Anasa%3Apds%3Acontext%3Ainstrument%3Amars2020.meda&version=1.3).
8. **NASA PDS Atmospheres.** [REMS: productos y documentación](https://pdsatmospheres.nmsu.edu/data_and_services/atmospheres_data/MARS/curiosity/rems.html).
9. **NASA/JPL (26/10/2023).** [NASA Is Locating Ice on Mars With This New Map](https://www.nasa.gov/solar-system/planets/mars/nasa-is-locating-ice-on-mars-with-this-new-map/). [Portal del proyecto SWIM](https://swim.psi.edu/).
10. **NASA.** [Mars Phoenix: resultados de la misión](https://science.nasa.gov/mission/mars-phoenix/).
11. **NASA (2021).** [Perseverance Makes Surprising Discoveries](https://www.nasa.gov/missions/mars-2020-perseverance/nasas-perseverance-mars-rover-makes-surprising-discoveries/).
12. **Artículo científico (2025).** [Redox-driven mineral and organic associations in Jezero Crater, Mars](https://doi.org/10.1038/s41586-025-09413-0).

**Acceso complementario:** [NASA PDS Orbital Data Explorer](https://ode.rsl.wustl.edu/).
