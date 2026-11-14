# matydrox

## Marte: condiciones de exploración y requisitos para análogos terrestres

**Proyecto:** NASA Space Apps Challenge 2026  
**Responsable de esta línea:** Matías  
**Fecha:** 14 de noviembre de 2026  
**Estado:** investigación inicial documentada; pendiente de revisión del equipo  
**Ubicación sugerida en GitHub:** `docs/investigacion/marte.md`

### 1. Propósito y alcance

Identificar las condiciones marcianas que una misión análoga necesita representar, para evaluar posteriormente sitios terrestres poco estudiados que puedan cubrir necesidades concretas de exploración.

Este documento organiza referencias científicas y propone líneas de análisis. No presenta un nuevo sitio terrestre validado, un ranking calculado ni resultados de procesamiento de datos. Las fuentes se consultaron durante la investigación previa a su elaboración; los productos científicos originales aún no se han descargado ni analizado.

La pregunta central es: **¿qué propiedades de un lugar terrestre permitirían estudiar o ensayar una tarea específica de exploración de Marte?**

### 2. Distinción inicial: Marte actual y Marte antiguo

Hay que separar las condiciones actuales necesarias para operar —atmósfera, temperatura, suelo, polvo y acceso al subsuelo— de los materiales y procesos que registran ambientes antiguos.

Una misión de perforación para obtener hielo necesita caracterizar el subsuelo actual. Una investigación de posibles biosignaturas puede centrarse en depósitos de antiguos lagos y su preservación. Ambas requieren analogías diferentes.

**Regla propuesta para el proyecto:** cada comparación debe identificar una región marciana, una tarea y la escala relevante. No asignar una única puntuación de parecido con todo Marte.

### 3. Regiones de referencia

| Región | Interés | Posible analogía terrestre | Tipo de evidencia y situación |
|---|---|---|---|
| Arcadia Planitia y sectores próximos de Amazonis | Hielo subsuperficial y potencial para futuras operaciones humanas | Suelo sobre hielo, terrenos periglaciales, excavación y muestreo | Observaciones orbitales y estudios de candidatos; no una base humana establecida |
| Jezero | Antiguo sistema fluvial y lacustre; habitabilidad y preservación | Depósitos deltaicos, sedimentos finos y alteración por agua | Observaciones orbitales y de Perseverance |
| Gale | Registro sedimentario y cambios ambientales | Secuencias sedimentarias, arcillas, sulfatos y alteración | Observaciones orbitales y de Curiosity |
| Oxia Planum | Materiales antiguos con arcillas y búsqueda de señales preservadas | Materiales alterados por agua, identificación mineralógica y muestreo | Caracterización orbital; sitio seleccionado para Rosalind Franklin |

Arcadia y Deuteronilus Mensae destacan en los estudios SWIM por reunir varias evidencias compatibles con materiales subsuperficiales ricos en hielo. Un trabajo de 2025 estudia tres candidatos en el límite Arcadia–Amazonis: AP-1, AP-8 y AP-9. La evidencia regional no establece condiciones idénticas en cada punto. [1, 2]

Jezero y Gale ofrecen evidencia desde la superficie sobre materiales y alteración por agua. Oxia dispone de un estudio de selección y contexto geológico: se describe como una región de bajo relieve de unos 200 km de extensión con unidades portadoras de arcillas. Esa extensión no es el tamaño de una futura área de comparación. [3, 4, 5]

### 4. Atmósfera y polvo

Como referencia general, Marte tiene una atmósfera dominada por CO₂ y una presión superficial aproximada de **6,35 mbar —635 Pa—**. La presión depende del lugar y del momento; no debe asignarse ese valor a todos los sitios. [6]

| Variable | Interés para la misión | Tratamiento propuesto |
|---|---|---|
| Presión y composición | Procesos físicos y funcionamiento de equipos | Registrar diferencias que el sitio terrestre no representa |
| Viento | Transporte de partículas y operaciones | Comparar el proceso relevante; una misma velocidad no garantiza el mismo efecto |
| Polvo atmosférico | Visibilidad, iluminación y exposición | Caracterizar cantidad, duración y variabilidad |
| Polvo depositado | Interacción con equipos y superficies | Investigar materiales y condiciones del ensayo |

**Fuentes locales de datos:** MEDA en Jezero y REMS en Gale. Los instrumentos incluyen observaciones de presión, temperatura del aire y del suelo, humedad y otras variables ambientales. Antes de usarlas hay que revisar disponibilidad, calibración y calidad de cada sensor y período. [7, 8]

La radiación óptica o ultravioleta registrada por una estación ambiental no debe tratarse automáticamente como una medición de toda la radiación ionizante relevante para una tripulación. Si esa dimensión se vuelve central, requerirá una línea específica de investigación.

### 5. Temperatura: comparar series locales

La caracterización térmica debe responder:

- ¿Qué temperatura tiene el suelo y cuál el aire?
- ¿Cómo evolucionan durante el día y entre estaciones?
- ¿Cuánto duran las condiciones relevantes para el ensayo?
- ¿A qué profundidad o altura se midió?
- ¿Qué observaciones faltan y qué correcciones requiere el instrumento?

REMS distingue temperaturas del suelo y del aire y ofrece productos procesados y documentación de calibración. [8]

#### Análisis propuesto

1. Seleccionar un lugar y período documentados.
2. Separar las variables físicas antes de comparar.
3. Obtener mínimos, máximos, amplitudes y evolución temporal con controles de calidad.
4. Buscar observaciones terrestres compatibles en escala y muestreo.
5. Explicar las diferencias que afectan a la tarea.

No comparar una media anual terrestre con una observación aislada marciana. Tampoco interpretar dos observaciones satelitales diarias como un ciclo completo. Estas son reglas de trabajo propuestas, no análisis ya ejecutados.

### 6. Agua, hielo y sales

| Tema | Pregunta | Aplicación análoga |
|---|---|---|
| Hielo actual | ¿Dónde está, a qué profundidad y con qué evidencia? | Detección, perforación, extracción y conservación de muestras |
| Agua antigua | ¿Qué estructuras y materiales registran su presencia? | Interpretación geológica y selección de muestras |
| Sales | ¿Cuáles hay y qué procesos registran? | Identificación mineralógica, alteración y preservación |

#### SWIM: hielo subsuperficial

El proyecto Subsurface Water Ice Mapping combina información de distintas misiones. La actualización presentada por NASA el **26 de octubre de 2023** incorporó imágenes de mayor resolución y cráteres recientes que exponen hielo, útiles para comprobar interpretaciones. Los mapas ayudan a localizar regiones potencialmente favorables para acceso al recurso. No determinan por sí solos cantidad y profundidad exactas en cada punto. [9]

#### Phoenix: evidencia local

Phoenix confirmó hielo de agua en el subsuelo de su lugar de aterrizaje y detectó percloratos en 2008. Son resultados locales que sirven como referencia; no justifican asignar la misma composición a toda la superficie marciana. [10]

#### Campos que debería contener nuestra ficha de hielo

- Tipo de evidencia: exposición observada, señal geofísica, morfología o modelo.
- Profundidad estimada y su incertidumbre, si están disponibles.
- Cobertura de suelo y propiedades documentadas.
- Escala y cobertura espacial del producto.
- Utilidad para una tarea específica.
- Medición que falta para confirmar la interpretación.

### 7. Geología: materiales, estructuras y procesos

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

### 8. Astrobiología

Conviene renombrar la rama del mapa como **“Habitabilidad, preservación y detección de biosignaturas”**.

| Concepto | Significado |
|---|---|
| Habitabilidad | Condiciones que podrían permitir vida |
| Preservación | Posibilidad de que sus señales sobrevivan |
| Detectabilidad | Posibilidad de medir esas señales con un instrumento |
| Origen biológico | Evidencia de que una señal procede de vida |

Los compuestos orgánicos no demuestran por sí solos un origen biológico. Un artículo de 2025 sobre la formación Bright Angel en Jezero describe asociaciones minerales, químicas y texturales como **biosignaturas potenciales**, que requieren investigación adicional para resolver su origen. [11, 12]

**Aplicación terrestre propuesta:** evaluar qué señales conserva un material y qué puede detectar un instrumento. El sitio no tiene que reproducir todas las condiciones marcianas para ser útil en esa pregunta, pero debe explicarse qué representa y qué no.

### 9. Datos que necesitamos localizar y comprobar

| Necesidad | Punto de partida | Comprobación pendiente |
|---|---|---|
| Ambiente local en Jezero | MEDA / PDS | Productos, intervalos, variables, calidad y formatos |
| Ambiente local en Gale | REMS / PDS | Descargar un período y separar aire, suelo y otros sensores |
| Hielo en latitudes medias | SWIM y estudios Arcadia–Amazonis | Resolución, significado del índice y evidencia por candidato |
| Geología de Oxia | Artículo de contexto y productos citados | Seleccionar unidad y área concreta |
| Relieve e imágenes planetarias | PDS y Orbital Data Explorer | Producto, escala, coordenadas y cobertura adecuada |
| Contrapartida terrestre | Earthdata y Copernicus | Disponibilidad de variables realmente comparables |

Los repositorios son puntos de acceso. La existencia de un portal no demuestra que todos los productos necesarios estén disponibles para todas las áreas.

### 10. Dos líneas iniciales propuestas

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

### 11. Entregable de la investigación de Marte

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

### 12. Rama de trabajo e integración

**Destino inicial recomendado: rama personal de Matías.** Este archivo documenta una línea de investigación, con propuestas aún pendientes de consenso.

Puede integrarse después a la rama general mediante revisión del equipo cuando:

- Las fuentes y afirmaciones principales hayan sido revisadas.
- El equipo entienda cuáles son resultados documentados y cuáles son propuestas.
- Las decisiones pendientes estén explícitas.
- Su estructura sea útil para las investigaciones de Luna y de sitios terrestres.

**No hace falta esperar a terminar toda la investigación para integrarlo.** Una versión inicial revisada puede vivir en la general y seguir ampliándose mediante aportes pequeños. Integrar el documento no implica que el equipo haya aprobado todas sus propuestas.

Este archivo se entrega para que el chat encargado del repositorio lo incorpore; no se ha realizado ninguna operación en GitHub.

### 13. Fuentes

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

---

## Arcadia–Amazonis: consolidación de evidencia para la búsqueda de análogos terrestres

**Proyecto:** NASA Space Apps Challenge 2026  
**Línea de investigación:** Marte — Matías  
**Fecha:** 14 de noviembre de 2026  
**Estado:** revisión documental e inspección inicial de datos; pendiente de revisión del equipo  
**Ruta en el repositorio:** `Estado del arte/Arcadia_Amazonis_consolidacion_de_evidencia.md`

### 1. Propósito y relación con el documento anterior

Este documento recopila lo avanzado desde `Investigacion_Marte_requisitos_para_analogos.md`: la elección exploratoria de Arcadia–Amazonis, la revisión de los archivos aportados, los datos disponibles para AP-1, AP-8 y AP-9, las incertidumbres detectadas y la corrección del enfoque de trabajo.

El objetivo sigue siendo **caracterizar sitios marcianos para buscar análogos terrestres**. Evaluar el hielo, el aterrizaje o la extracción de recursos son partes posibles de esa caracterización, no objetivos que sustituyan automáticamente el desafío.

El documento anterior planteó dos líneas iniciales —hielo y operaciones en Arcadia–Amazonis; materiales y búsqueda de señales en Oxia/Jezero—. Se comenzó por Arcadia–Amazonis para examinar información concreta. Esta elección fue exploratoria: no surgió de un ranking cuantitativo de todas las regiones de Marte.

**Límite de esta entrega:** consolida lo aprendido. La siguiente etapa será interpretar conjuntamente esta evidencia para decidir qué características buscar y exigir a los candidatos terrestres. Esa selección de requisitos y la búsqueda de nuevos sitios no se desarrollan aquí.

### 2. Enfoque acordado

La secuencia de trabajo queda definida así:

1. Identificar y delimitar referencias marcianas.
2. Recopilar sus características y fuentes, conservando escalas e incertidumbres.
3. Determinar, en una etapa posterior, qué propiedades son relevantes para distintas actividades análogas.
4. Buscar y caracterizar candidatos terrestres con evidencia comparable.
5. Presentar las correspondencias y diferencias en un catálogo visual filtrable según el objetivo de la misión análoga.

No se exige que un lugar terrestre reproduzca todo Marte. La utilidad de una analogía dependerá de la actividad y de las propiedades que efectivamente represente. La originalidad de un sitio poco estudiado debe acompañarse de evidencia suficiente.

### 3. Material revisado

| Fuente aportada | Contenido revisado | Función |
|---|---|---|
| Luzzi et al., 2025 | Artículo de 38 páginas; tablas, métodos y resultados de AP-1/AP-8/AP-9 | Referencia principal para los sitios marcianos |
| Anglés y Li, 2017 | Artículo de 33 páginas; localizaciones comparadas, campaña y mineralogía | Antecedente terrestre de Qaidam |
| `MARTE 2026 .docx` | Notas sobre Arcadia y texto de divulgación de NASA sobre SWIM | Síntesis inicial, contrastada con los artículos |
| `SWIMProducts.zip` | Cuatro ZIP internos, README, 27 GeoTIFF y componentes de un shapefile | Inspección de datos geográficos auxiliares |

La revisión incluyó extracción de texto de ambos artículos, inspección visual de tablas relevantes, lectura de las notas y descompresión de los paquetes SWIM. Se inspeccionaron valores y metadatos de las diez capas de la carpeta 0–1 m, se compararon sus archivos correspondientes con la carpeta 1–5 m y se extrajeron valores puntuales en las coordenadas publicadas de los tres sitios.

Los datos de los artículos no se recalcularon desde las imágenes originales. Las extracciones puntuales de SWIM sí se realizaron sobre los archivos entregados. No se ejecutó una comparación nueva Marte–Tierra.

### 4. Unidad geográfica de análisis

La región general es **Arcadia–Amazonis**, y las referencias locales son **AP-1, AP-8 y AP-9**, situadas en el límite entre Amazonis septentrional y Arcadia Planitia.

El artículo distingue el punto del sitio de aterrizaje del área circundante. Sus mapas geomorfológicos abarcan las huellas de imágenes HiRISE; no deben tratarse como elipses de aterrizaje ni como polígonos del mismo tamaño. [L, pp. 5–6]

| Sitio | Latitud | Longitud este 0–360° | Longitud equivalente −180–180° |
|---|---:|---:|---:|
| AP-1 | 39,8° N | 202,1° E | −157,9° |
| AP-8 | 40,75° N | 201,3° E | −158,7° |
| AP-9 | 40,02° N | 203,35° E | −156,65° |

La última columna es una conversión aritmética para facilitar usos cartográficos. No cambia el cuerpo planetario ni convierte las coordenadas en coordenadas terrestres.

### 5. Caracterización documentada de los tres sitios

#### 5.1 Relieve, polígonos e indicadores

| Propiedad | AP-1 | AP-8 | AP-9 |
|---|---:|---:|---:|
| Desnivel máximo en la huella HiRISE estudiada | 31 m | 140 m | 10 m |
| Dato local adicional de relieve | No desglosado aquí | 8 m en los 2,5 km² inmediatos al sitio | No desglosado aquí |
| Diámetro modal de polígonos | 11,7 m | 12,1 m | 10,7 m |
| Desviación estándar de diámetros | 3,3 m | 3,5 m | 3,1 m |
| Polígonos | Identificados | Identificados | Identificados |
| Cráteres expandidos | Identificados | Identificados | Identificados |
| Cráteres expandidos invertidos | Identificados | Identificados | Identificados |
| Formas semejantes a pingos | Identificadas | No identificadas | Identificadas |
| Terreno «brain coral» | Identificado | Identificado | No identificado |
| Crestas arqueadas | Identificadas | Identificadas | No identificadas |

Fuentes: relieve, página 5; diámetros, página 15; presencia de formas, tabla 2 de la página 18. [L]

**Interpretación de alcance:** AP-1 presenta la mayor diversidad de las categorías de formas incluidas en esa tabla. AP-8 combina un sector inmediato de bajo relieve con una huella más heterogénea. AP-9 tiene el menor desnivel de las huellas reportadas. Estas descripciones no constituyen un ranking de idoneidad, seguridad o facilidad de desplazamiento.

Los desniveles no se calcularon sobre áreas equivalentes. Tampoco son pendientes. «No identificado» se limita a la cartografía del área estudiada y no prueba ausencia regional.

#### 5.2 Microrelieve de polígonos

El artículo distingue polígonos de centro elevado suave y polígonos de centro elevado con montículo. En una submuestra de 35 de cada tipo por región —105 por tipo en total—, los segundos presentan alturas típicas de 0,5–1,6 m, moda de 0,8 m y desviación estándar de 0,25 m. Los de centro elevado suave no superan 0,4 m, con moda de 0,2 m y desviación estándar de 0,1 m. [L, p. 15]

Estas estadísticas se reportan para el conjunto muestreado, no como distribuciones independientes completas de cada sitio. La precisión vertical de los modelos es del orden de decenas de centímetros, por lo que las alturas menores presentan incertidumbre considerable.

El diámetro modal es el valor más frecuente de la distribución estimada; no debe rotularse como diámetro medio. La desviación estándar describe dispersión, no incertidumbre instrumental.

### 6. Hielo: separar observación, inferencia y contexto

| Evidencia | Qué permite afirmar | Qué no permite afirmar |
|---|---|---|
| Polígonos de contracción y otras formas interpretadas como periglaciales | Procesos relacionados con hielo en la historia del terreno | Profundidad actual medida en cada punto |
| Estimación de unos 8–12 cm a partir del espaciamiento poligonal | Hipótesis sobre profundidad cuando se estableció el patrón; los autores favorecen aproximadamente 8–10 cm | Hielo confirmado hoy a 10 cm en los tres sitios |
| Hielo expuesto en un impacto a unos 23 km de AP-1 | Evidencia cercana de hielo subsuperficial | Confirmación directa bajo AP-1 |
| Exposición 50–60 cm bajo la elevación máxima del borde del cráter | Posición topográfica de hielo visible en ese cráter | Profundidad original exacta antes del impacto |
| Cráteres recientes con y sin exposición de hielo | Variación posible de profundidad o distribución | Ausencia definitiva de hielo bajo cada cráter sin exposición |

Fuentes: secciones 3.3 y 4.1 y conclusiones. [L, pp. 16–17, 25–26, 32–33]

La inferencia a partir de polígonos depende del contexto térmico y de propiedades del terreno que no se conocen por completo. La profundidad pudo cambiar desde la formación de las estructuras. El impacto y los derrumbes también pueden modificar la posición del hielo expuesto.

**Profundidad hasta el hielo**, **espesor del depósito**, **contenido de hielo** y **volumen extraíble** deben permanecer como variables distintas.

### 7. Valores SWIM publicados en el artículo

| Sitio | Combinado 0–1 m | Geomorfología | Neutrones | Potencia radar superficial | Térmico | Propiedades dieléctricas estimadas |
|---|---:|---:|---:|---:|---:|---:|
| AP-1 | 0,20 | 0,63 | 0,29 | 0 | 0 | 0,10 |
| AP-8 | 0,39 | 0,75 | 0,51 | 0 | 0,33 | 0,39 |
| AP-9 | 0,43 | 0,75 | 0,51 | 0 | 0,33 | 0,55 |
| Cráter con exposición de hielo | 0,30 | 0,75 | 0,29 | 0,50 | 0 | 0 |

Transcripción de la tabla 3, página 19. [L]

Son índices de consistencia de evidencias. **0,43 no equivale a 43 % de probabilidad, 43 % de hielo ni una profundidad.** No se recalcularon con el ZIP aportado.

Los autores destacan que el cráter con hielo expuesto tiene un índice combinado menor que AP-8 y AP-9. Esto ilustra límites de una evaluación regional cuando se interpreta localmente. No invalida toda la cartografía ni permite corregir índices sin un método documentado.

### 8. Inventario e inspección del paquete SWIM

#### 8.1 Contenido

| Paquete interno | Contenido |
|---|---|
| `SWIM4MIM_G_0_1_Ancillary.zip` | 10 capas geomorfológicas auxiliares y README |
| `SWIM4MIM_G_1_5_Ancillary.zip` | 10 capas geomorfológicas auxiliares y README |
| `SWIM4MIM_G_5_Ancillary.zip` | 7 capas geomorfológicas auxiliares y README |
| `SWIM4MIM_RZ_Ancillary.zip` | Geometría de zonas de reconocimiento y README |

Las capas representan cráteres expandidos, rellenos, depósitos glaciares, manto dependiente de latitud, cráteres pedestal, polígonos, cráteres de molde anular, terreno festoneado, cráteres aterrazados y terreno texturado. Los nombres deben conservarse junto a los originales para evitar ambigüedad. [S]

#### 8.2 Propiedades verificadas

| Propiedad | Resultado |
|---|---|
| Proyección inspeccionada | Cilíndrica equidistante marciana, ESRI:103885 |
| Dimensiones de las capas 0–1 m | 7.200 × 2.400 píxeles |
| Tamaño de píxel proyectado | 2.963,735 m; aproximadamente 3 km |
| Cobertura declarada en README | 0–360° E; 60° S–60° N |
| Valor NoData declarado | −30 |
| Comparación 0–1 m frente a 1–5 m | Los diez pares de GeoTIFF son idénticos byte por byte |
| Zonas de reconocimiento | Geometría legible; falta el componente `.dbf` de atributos |

La escala es regional. El tamaño de píxel en una proyección cilíndrica no debe confundirse con una superficie terrestre uniforme ni utilizarse directamente para detectar obstáculos pequeños.

#### 8.3 Ponderaciones y significado de los intervalos

Los README asignan pesos diferentes a algunas de las mismas capas según el intervalo. Por ejemplo, los depósitos glaciares pasan de 0,75 en 0–1 m a 1 en 1–5 m; los polígonos pasan de 1 a 0,5. [S]

Por tanto, no son dos observaciones independientes que midan físicamente la profundidad del hielo: son datos auxiliares compartidos para una interpretación por intervalos. El README de 1–5 m contiene además una referencia textual a «1-0m», inconsistente con el nombre del paquete; no se corrigió el original.

#### 8.4 Hallazgos de calidad

- La capa de polígonos contiene valores próximos a **−3,4 × 10³⁸**, además del NoData declarado de −30. Deben aclararse y tratarse explícitamente antes de calcular estadísticas.
- Esa capa también presenta algunos valores superiores a 1. No se debe asumir sin documentación que sea una probabilidad o una máscara binaria.
- Las demás capas 0–1 m inspeccionadas contienen valores 0 y 1. Su interpretación física debe seguir el método de la fuente; un cero no equivale a ausencia de hielo.
- No se incluyeron mapas combinados ni todas las capas térmicas, de neutrones y radar de la tabla de Luzzi.
- No se aplicaron correcciones a los archivos originales ni se calculó un índice combinado nuevo.

#### 8.5 Extracciones puntuales realizadas

Se transformaron las coordenadas de los sitios al sistema de los raster y se leyó el píxel correspondiente en las capas 0–1 m. Los siguientes son valores auxiliares originales:

| Capa | AP-1 | AP-8 | AP-9 |
|---|---:|---:|---:|
| Cráteres expandidos | 1 | 1 | 1 |
| Manto dependiente de latitud | 1 | 1 | 1 |
| Terreno texturado | 1 | 1 | 1 |
| Terreno festoneado | 0 | 0 | 1 |
| Cráteres aterrazados | 0 | 1 | 0 |

Son descriptores de píxeles regionales; no porcentajes de cobertura del sitio ni inventarios de todas las formas presentes. No deben confundirse con las mediciones y valores SWIM publicados en el artículo.

### 9. Qaidam: evidencia terrestre ya reunida

El artículo de Anglés y Li documenta sectores del oeste de Qaidam y los compara con estructuras marcianas. Es un antecedente útil para nuestro catálogo, pero no demuestra una analogía integral con Arcadia. [Q]

#### 9.1 Sectores identificados

| Coordenadas terrestres de un ejemplo | Característica documentada |
|---|---|
| 38,75° N; 91,75° E | Terrenos poligonales |
| 38,32° N; 91,27° E | Cárcavas |
| 39,16° N; 92,00° E | Valles fluviales y abanicos aluviales |
| 37,61° N; 92,23° E | Yardangs |
| 38,37° N; 91,63° E | Campos de dunas |
| 38,49° N; 91,74° E | Estructuras anulares |

Fuente: tabla 1, página 3 del PDF, página impresa 858. Son localizaciones de ejemplos ilustrados, no límites completos de sitios de prueba.

#### 9.2 Campaña y materiales

La investigación describe una expedición de diez días en agosto de 2016, nueve localidades y 78 muestras. Incluye microscopía electrónica, difracción de rayos X y análisis termogravimétrico de tres muestras de yeso. Documenta halita, yeso y otros minerales, con limitaciones en la identificación de fases menores. [Q, secciones 3.1–3.2]

Las propiedades de una muestra no deben atribuirse automáticamente a todos los sectores de la tabla. El parecido geométrico de polígonos tampoco establece que tengan el mismo proceso de formación o hielo subsuperficial comparable.

**Estado para el proyecto:** referencia terrestre documentada por sectores y dimensiones; no seleccionado como análogo integral de AP-1, AP-8 o AP-9.

### 10. Correcciones a la síntesis inicial

| Afirmación inicial o riesgo de interpretación | Formulación que conservaremos |
|---|---|
| «Se filtraron cuatro regiones de Marte» | Se eligieron exploratoriamente cuatro referencias; no hubo filtro cuantitativo global |
| «Arcadia es plana» | Hay sectores de bajo relieve; la variabilidad y escala deben especificarse |
| «Hielo a 10 cm» | Estimación indirecta asociada al patrón poligonal y su formación, no profundidad actual confirmada |
| «Hielo a 50–60 cm en AP-1» | Exposición en un cráter situado aproximadamente a 23 km, medida respecto a su borde |
| «Depósitos de 30–80 m» | Cifra de las notas pendiente de fuente y delimitación; no se asigna a los tres sitios |
| «SWIM 0,43 = 43 %» | Índice de consistencia; no probabilidad, pureza o profundidad |
| «Capas de 0–1 y 1–5 m son mediciones distintas» | Los pares de raster son idénticos y cambian algunas ponderaciones documentadas |
| «Qaidam reproduce Arcadia» | Hay comparaciones posibles por dimensión; aún no una correspondencia integral demostrada |
| «Sitio favorable para aterrizar = sitio validado» | Se trata de candidatos evaluados bajo criterios y escalas de estudios concretos |

Las notas `MARTE 2026 .docx` se conservan como síntesis de trabajo; los artículos y productos identificados respaldan los campos técnicos. [N]

### 11. Estado de la caracterización y vacíos

| Dimensión | Evidencia disponible | Limitación pendiente |
|---|---|---|
| Ubicación | Coordenadas de los tres sitios | Definir polígonos operativos de comparación |
| Relieve | Desniveles e imágenes/modelos identificados | Comparación sobre áreas y escalas homogéneas |
| Morfología | Inventarios y tamaños de polígonos | Recuperar cartografía digital y su cobertura |
| Hielo | Indicios, modelos y exposición cercana | Profundidad y continuidad actuales por sitio |
| Materiales | Contexto regional | Composición y granulometría local suficientes |
| Ambiente térmico | Contexto general | Valores específicos con período y escala |
| Polvo y viento | Contexto general | Caracterización local útil para una actividad definida |
| Propiedades mecánicas | Información insuficiente en lo revisado | Resistencia, cohesión y comportamiento del subsuelo |
| Radiación y presión | Contexto planetario | Definir su relevancia para las actividades análogas |

Los datos faltantes permanecen como desconocidos. No se sustituirán por promedios de Marte presentados como mediciones de AP-1/AP-8/AP-9.

### 12. Productos identificados para continuar después

#### 12.1 Imágenes y pares estéreo del artículo

| Sitio | Imagen principal | Par estéreo |
|---|---|---|
| AP-1 | `ESP_052490_2200` | `ESP_052424_2200` |
| AP-8 | `ESP_043220_2210` | `ESP_042930_2210` |
| AP-9 | `ESP_060811_2205` | `ESP_060323_2205` |

La tabla 1 de Luzzi indica 25 cm/píxel para las imágenes proyectadas; la escala original de estos pares ronda 30–32 cm/píxel. El remuestreo no crea detalle nuevo. No confundir escala de imagen con resolución horizontal del modelo de elevación o precisión vertical. [L, p. 6]

#### 12.2 Cartografía vectorial

El artículo enlaza el conjunto **Geomorphic maps of candidate landing sites in northern Amazonis Planitia**, Luzzi, Nodjoumi y Heldmann (2024), DOI [10.5281/zenodo.13647425](https://doi.org/10.5281/zenodo.13647425).

Este conjunto fue identificado en la bibliografía, pero no se descargó ni inspeccionó en la revisión consolidada aquí. Las imágenes originales pueden localizarse mediante [PDS Orbital Data Explorer](https://ode.rsl.wustl.edu/).

### 13. Punto de cierre y siguiente etapa

Quedan consolidadas tres sitios de referencia marcianos de una misma región, varios sectores terrestres documentados de Qaidam y un inventario de las capas auxiliares SWIM disponibles.

**Siguiente etapa:** definir qué buscar en la Tierra y qué requisitos exigir según el objetivo de la misión análoga. No se decide aquí una lista final de requisitos, ponderaciones, candidatos nuevos ni un ranking.

Para reproducir las extracciones de SWIM, queda pendiente registrar la versión o suma de verificación del ZIP, los nombres exactos de las capas, la transformación de coordenadas y el tratamiento de NoData. Las comprobaciones del paquete se conservan como resultados reportados en el borrador; quedan pendientes de reproducción por el equipo.

### 14. Fuentes y trazabilidad

- **[L] Luzzi et al. (2025).** *Geomorphological Evidence of Near-Surface Ice at Candidate Landing Sites in Northern Amazonis Planitia, Mars*. [DOI](https://doi.org/10.1029/2024JE008724). Las páginas citadas corresponden a las 38 páginas del PDF.
- **[Q] Anglés, A. y Li, Y. (2017).** *The western Qaidam Basin as a potential Martian environmental analogue: An overview*. [DOI](https://doi.org/10.1002/2017JE005293).
- **[S] Paquete SWIM aportado.** `SWIMProducts.zip`. Los README solicitan citar Morgan, G. A., Putzig, N. E. y colaboradores (2025), *Refined Mapping of Subsurface Water Ice on Mars to Support Future Missions*, Planetary Science Journal, 6, 29, [DOI](https://doi.org/10.3847/PSJ/ad9b24). El inventario y las comprobaciones descritas proceden de los archivos aportados; no implican revisión completa de ese artículo metodológico.
- **[N] Notas de trabajo.** `MARTE 2026 .docx` (archivo de trabajo del equipo).
- **Contexto previo.** [NASA, 26 de octubre de 2023: cartografía del hielo marciano](https://www.nasa.gov/solar-system/planets/mars/nasa-is-locating-ice-on-mars-with-this-new-map/) y [portal SWIM](https://swim.psi.edu/).
- **Documento anterior.** [Investigacion_Marte_requisitos_para_analogos.md](Estado%20del%20arte/Investigacion_Marte_requisitos_para_analogos.md).
