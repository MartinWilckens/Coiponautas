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
**Estado:** versión ampliada con caracterización regional de Arcadia; fichas individuales y extracción climática pendientes  
**Ruta en el repositorio:** `matydrox.md`

### 1. Propósito y relación con el documento anterior

Este documento recopila lo avanzado desde `Investigacion_Marte_requisitos_para_analogos.md`: la elección exploratoria de Arcadia–Amazonis, la revisión de los archivos aportados, los datos disponibles para AP-1, AP-8 y AP-9, las incertidumbres detectadas y la corrección del enfoque de trabajo.

El objetivo sigue siendo **caracterizar sitios marcianos para buscar análogos terrestres**. Evaluar el hielo, el aterrizaje o la extracción de recursos son partes posibles de esa caracterización, no objetivos que sustituyan automáticamente el desafío.

El documento anterior planteó dos líneas iniciales —hielo y operaciones en Arcadia–Amazonis; materiales y búsqueda de señales en Oxia/Jezero—. Se comenzó por Arcadia–Amazonis para examinar información concreta. Esta elección fue exploratoria: no surgió de un ranking cuantitativo de todas las regiones de Marte.

**Alcance de esta actualización:** incorpora una caracterización regional de Arcadia en la sección 11, conservando los datos locales ya reunidos. Distingue resultados publicados, interpretaciones y parámetros todavía no medidos. Las fichas individuales de AP-1, AP-8 y AP-9 serán la próxima etapa; después se definirán requisitos para buscar análogos terrestres. No se presenta esta revisión documental como una caracterización instrumental completa.

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
| «Depósitos de 30–80 m» | Fuente recuperada: Bramson et al. (2017), basada en interpretación radar previa; espesor inferido y discutido, no profundidad hasta el hielo ni valor de cada AP |
| «SWIM 0,43 = 43 %» | Índice de consistencia; no probabilidad, pureza o profundidad |
| «Capas de 0–1 y 1–5 m son mediciones distintas» | Los pares de raster son idénticos y cambian algunas ponderaciones documentadas |
| «Qaidam reproduce Arcadia» | Hay comparaciones posibles por dimensión; aún no una correspondencia integral demostrada |
| «Sitio favorable para aterrizar = sitio validado» | Se trata de candidatos evaluados bajo criterios y escalas de estudios concretos |

Las notas `MARTE 2026 .docx` se conservan como síntesis de trabajo; los artículos y productos identificados respaldan los campos técnicos. [N]

### 11. Caracterización regional ampliada de Arcadia

#### 11.1 Qué región estamos describiendo

**Arcadia es una referencia regional heterogénea.** Para este proyecto interesan especialmente sus llanuras de latitudes medias y la transición hacia Amazonis septentrional. No deben combinarse como si fueran un solo sitio todos los terrenos que un artículo denomina «Arcadia».

| Referencia espacial | Cobertura de la evidencia | Uso correcto |
|---|---|---|
| Franja de Ramsdale et al. (2019) | 300 km de ancho, 30–80° N, centrada en 170° O / 190° E | Contexto regional y variación latitudinal; no mapa de los tres AP [R1] |
| Unidades sinuosas estudiadas por Hibbard et al. (2018) | 38–40° N; 156–166° O, equivalentes a 194–204° E | Contrastar superficies sinuosas con terrenos adyacentes [R2] |
| Referencia térmica de Piqueux et al. (2019) | Ejemplo en 45° N, 190° E | Inferencia térmica de hielo somero; no corresponde a AP-1/8/9 [R6] |
| AP-1, AP-8 y AP-9 | Coordenadas y huellas de las secciones 4–5 | Evidencia local que después tendrá fichas individuales [L] |

Estas coberturas son ámbitos de estudios, no una delimitación oficial nueva de Arcadia. La ficha regional del catálogo deberá contener subunidades y procedencia espacial de cada atributo.

#### 11.2 Geología, materiales e historia del terreno

La cartografía de Ramsdale et al. relaciona la transición meridional hacia Amazonis con llanuras de probable origen volcánico y reconoce un manto rico en hielo que recubre materiales previos. La distribución de hidrógeno y de formas superficiales cambia con la latitud. No corresponde describir toda la región como un único afloramiento de basalto. [R1]

Hibbard et al. (2021) interpretan tres estructuras sinuosas como glaciares enterrados bajo detritos, apoyándose en morfología, propiedades térmicas y radar. Su semejanza con antiguas corrientes de hielo estancadas es una interpretación, no una medición de flujo actual. [R3]

**Esquema de trabajo propuesto:** distinguir una cobertura superficial de partículas, un subsuelo con distribución de hielo variable y materiales geológicos subyacentes. Este esquema organiza preguntas; no fija tres capas universales con espesores conocidos.

| Material o propiedad | Caracterización defendible | Límite |
|---|---|---|
| Cobertura superficial de las unidades sinuosas | Interpretada como suelo predominantemente arenoso, suelto o poco cohesivo a partir de propiedades térmicas e imágenes [R2] | No hay aquí curva granulométrica medida ni ensayo de cohesión |
| Terrenos vecinos | Menor inercia térmica, compatibles con una mayor influencia de partículas finas [R2] | No equivale a espesor de polvo medido |
| Hielo | Evidencias independientes de hielo subsuperficial; arquitectura y contenido variables [L, R4–R6] | No es una capa uniforme confirmada bajo toda Arcadia |
| Mineralogía superficial | No se recuperó una identificación cuantitativa representativa de los AP | No asignar porcentajes de basaltos, arcillas o sulfatos por analogía con otros lugares |
| Sales y percloratos | No quedaron caracterizados localmente con las fuentes revisadas | No trasladar concentraciones de Phoenix ni composiciones de Qaidam |

La historia relevante para análogos incluye acumulación y preservación de hielo, pérdida por sublimación, contracción térmica, impactos y modificación eólica. No todas las formas conservadas tienen que estar formándose hoy. Los cambios de oblicuidad son parte de las explicaciones propuestas para la historia del hielo; no una prueba de su edad en cada AP. [L, R3, R4]

#### 11.3 Relieve, rugosidad y obstáculos

Golombek et al. (2021) publican elevaciones redondeadas de **−3,9 km respecto al geoide MOLA** para los tres AP. También identifican superficies poligonales suaves de Arcadia que satisfacen su criterio de pendiente inferior a 5° sobre 10 m. Este resultado no se aplica a todo el terreno regional ni reemplaza un mapa de pendientes. [R7]

Para la comparación terrestre deben conservarse por separado:

- **Elevación:** contexto topográfico y atmosférico; −3,9 km en Marte no exige un análogo terrestre a esa elevación.
- **Pendiente y longitud de base:** inclinación calculada sobre una distancia explícita.
- **Rugosidad:** variación de altura a escalas comparables con ruedas, patas o recorridos.
- **Obstáculos:** diámetro, altura, abundancia y distribución de rocas, grietas y crestas.

La sección 5 ya documenta relieve poligonal métrico y diámetros del orden de diez metros. Eso permite describir una superficie con microrelieve aun cuando la llanura sea regionalmente poco inclinada. Siguen pendientes percentiles de pendiente y densidades de obstáculos obtenidos con un mismo método para los tres sitios. [L]

#### 11.4 Propiedades térmicas: cifras disponibles y significado

La inercia térmica describe la resistencia de una superficie a cambiar de temperatura. No es una temperatura ni determina por sí sola un tamaño de grano.

| Parámetro | Valor publicado | Alcance y naturaleza |
|---|---:|---|
| Inercia térmica de unidades sinuosas | 200–250 J·m⁻²·K⁻¹·s⁻½ | Resultado orbital publicado en resumen de congreso de 2018; no distribución individual de AP [R2] |
| Inercia térmica de terrenos circundantes | 100–200 J·m⁻²·K⁻¹·s⁻½ | Mismo estudio y comparación; no rango completo de Arcadia [R2] |
| Inercia térmica regional usada por Bramson et al. | 196 J·m⁻²·K⁻¹·s⁻½ | Parámetro adoptado a partir de TES [R4, tabla 1] |
| Albedo adoptado para Arcadia | 0,23 | Valor representativo del área de estudio, no constante regional [R4] |

Los contrastes apoyan la separación de unidades para buscar análogos, pero admiten distintas combinaciones de partículas, compactación y estratificación. **Una coincidencia de inercia térmica no demuestra igualdad mineralógica ni mecánica.**

No se obtuvo en esta revisión una serie de temperatura superficial que permita publicar máximas, mínimas y amplitudes diarias o estacionales de nuestra área. Tampoco se ejecutó un modelo térmico nuevo. Por ello, no se rellenan esos campos con extremos planetarios de Marte.

La investigación térmica sí aporta algo concreto: Piqueux et al. ajustan temperaturas estacionales de MCS y THEMIS con un modelo de dos capas, suponiendo hielo en la inferior. Sus mapas regionales tienen 3 píxeles por grado; en el ejemplo de 45° N, 190° E infieren hielo a pocos centímetros. Es una estimación dependiente del modelo y espacialmente distinta de los AP. [R6]

Para obtener temperaturas comparables habrá que registrar coordenadas, hora solar local, estación marciana —longitud solar, Ls—, año marciano, polvo y si la variable corresponde al suelo o al aire. Eso se resolverá con extracción de productos o modelado, no añadiendo más promedios generales a la bibliografía.

#### 11.5 Hielo y estructura del subsuelo: qué queda resuelto

**La evidencia de hielo somero y la hipótesis de un depósito grueso son cuestiones diferentes.** La primera no valida automáticamente la segunda.

| Cuestión | Resultado regional | Estado |
|---|---|---|
| ¿Existe hielo cercano a la superficie? | Exposiciones por impactos y múltiples indicadores orbitales, además de la evidencia geomorfológica de la sección 6 | Respaldado para localidades observadas; no confirmado punto por punto [L, R6] |
| ¿De dónde provienen los 30–80 m? | Bramson et al. (2017) recogen espesores derivados de la interpretación radar de depósitos de Arcadia | Fuente identificada; no profundidad de enterramiento [R4] |
| ¿Es todo ese espesor hielo dominante? | Campbell y Morgan encuentran pérdidas radar incompatibles con predominio de hielo en grandes fracciones del espesor investigado | Interpretación discutida [R5] |
| ¿Qué muestran las unidades sinuosas? | Hibbard et al. reúnen evidencia a favor de glaciares cubiertos por detritos | Hipótesis respaldada por varios indicadores; no sondeo directo [R3] |
| ¿Cuánto hielo hay bajo cada AP? | No determinado aquí de forma directa | Pendiente; SWIM no sustituye el contenido volumétrico [L, S] |

Bramson et al. modelan preservación durante 21 millones de años y una cobertura residual que limita la pérdida de hielo. Es un mecanismo de supervivencia compatible con su interpretación, no una datación ni una prueba de continuidad bajo los tres sitios. [R4]

Almacenar separadamente: profundidad del techo, espesor, fracción de hielo, porosidad, material de cobertura y método de inferencia. Cuando dos estudios difieran, conservar ambas hipótesis; no promediarlas como si fueran medidas equivalentes.

**Actualización metodológica de 2026:** Courville et al. publicaron un enfoque probabilístico para SWIM. Esto no convierte retroactivamente los índices de la tabla 3 de Luzzi ni los raster auxiliares aportados en probabilidades. El catálogo debe identificar método y versión. Se verificó la publicación y su enfoque; no se descargaron ni calcularon sus productos en esta entrega. [R13]

#### 11.6 Atmósfera, viento y polvo

El contexto planetario es una atmósfera tenue dominada por CO₂ —aproximadamente 95 %—. Eso no constituye una medida de presión en Arcadia. [R10]

Heavens (2017) estudia tormentas de polvo texturadas en el noreste de Amazonis–suroeste de Arcadia, con imágenes y observaciones atmosféricas. Documenta estructura y dinámica de tormentas y enfriamiento superficial bajo sus nubes. Por tanto, la zona no puede representarse como un desierto frío atmosféricamente inactivo. [R8]

Stanzel et al. (2006) identificaron remolinos activos en Arcadia mediante HRSC. Eso acredita actividad eólica regional, pero no da una tasa anual ni una velocidad del viento a la altura de un instrumento en AP-1. [R9]

| Campo | Qué puede registrarse ahora | Qué falta para cuantificarlo |
|---|---|---|
| Actividad de polvo | Observada regionalmente; separar remolinos y tormentas | Frecuencia por área, estación y cobertura de observación |
| Presión | Contexto de baja presión; no rango local establecido aquí | Serie modelada con elevación y estación explícitas |
| Viento | Procesos eólicos observados | Velocidad, dirección, altura de referencia y variabilidad local |
| Opacidad del polvo | Variable ambiental necesaria | Serie con longitud de onda, normalización y fechas |
| Depósito sobre equipos | No cuantificado para los AP | No deducirlo solamente de presencia de tormentas |

La Mars Climate Database permite obtener temperatura, presión, viento y otras variables mediante simulaciones y escenarios de polvo. Sus salidas deben etiquetarse como **modeladas**. La climatología media no representa por sí sola una tormenta extrema ni ráfagas sobre microrelieve. [R11]

La climatología de polvo de LMD ofrece opacidad de columna a 9,3 µm, incluyendo productos normalizados a 610 Pa y a presión superficial. Es necesario conservar esa distinción antes de comparar valores. [R12]

#### 11.7 Resistencia del suelo, excavación y movilidad

La caracterización mecánica permanece indirecta. Las imágenes y propiedades térmicas ayudan a formular hipótesis sobre partículas y cobertura; **no proporcionan un ensayo de penetración, una resistencia portante o una curva de compactación**.

Golombek et al. excluyen de su selección superficies de inercia térmica inferior a 100 J·m⁻²·K⁻¹·s⁻½ por su posible asociación con polvo espeso poco favorable para soporte o radar. Es un criterio de selección, no una frontera universal que garantice firmeza por encima de 100. [R7]

Para evitar una falsa caracterización, quedan sin valor numérico local: cohesión, ángulo de fricción, densidad aparente, resistencia a penetración, abrasividad, hundimiento y esfuerzo de excavación. La futura ficha podrá contener hipótesis de material para ensayos, claramente separadas de mediciones marcianas. No se trasladan parámetros mecánicos de InSight o Phoenix a Arcadia.

#### 11.8 Agua líquida, biología, cuevas y límites de analogía

En la documentación incorporada no queda establecida una reserva actual de agua líquida, una biosignatura confirmada ni un sistema de cuevas en las áreas AP. Esos campos se registran como **no caracterizados**, no como ausencias demostradas. La presencia de hielo, por sí sola, no confirma habitabilidad ni conservación de material biológico.

La gravedad y el ambiente radiativo pertenecen al contexto marciano y no son criterios que un paisaje terrestre reproduzca íntegramente. Tampoco se asigna a Arcadia una dosis medida por Curiosity en otra región. Para experimentos de presión, radiación o comportamiento físico dependiente de gravedad harán falta condiciones controladas o una justificación de escala; el lugar terrestre puede seguir siendo útil para otras dimensiones.

#### 11.9 Balance de esta actualización

| Dimensión | Avance logrado | Pendiente real |
|---|---|---|
| Contexto geológico | Distinción entre materiales previos, cobertura y unidades interpretadas como glaciares | Composición local y estratigrafía verificable |
| Relieve | Contexto de llanura baja y datos locales conservados | Estadísticas homogéneas de pendientes y obstáculos |
| Superficie | Contraste térmico cuantificado entre unidades sinuosas y vecinas | Granulometría y espesores medidos |
| Hielo | Fuente del espesor recuperada; hipótesis contrapuestas documentadas | Profundidad, pureza y continuidad por sitio |
| Temperatura | Propiedades térmicas y método de observación identificados | Ciclos diarios y estacionales extraídos o modelados |
| Atmósfera y polvo | Actividad regional demostrada y productos identificados | Series locales de presión, viento y opacidad |
| Mecánica | Alcance de inferencias delimitado | Parámetros geotécnicos directos |

**Resultado:** disponemos de una caracterización documental regional más sólida para preparar las fichas individuales. No disponemos todavía de una caracterización numérica completa de todos los campos. Los vacíos que quedan requieren productos concretos, procesamiento o mediciones nuevas; no se resuelven atribuyendo a toda Arcadia un valor único.

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

**La siguiente etapa será elaborar las fichas individuales de AP-1, AP-8 y AP-9**, manteniendo separados los datos propios y el contexto regional. Después se traducirán sus características a requisitos de análogos terrestres según la actividad. No se decide aquí una lista final de requisitos, ponderaciones, candidatos nuevos ni un ranking.

Para reproducir las extracciones de SWIM, queda pendiente registrar la versión o suma de verificación del ZIP, los nombres exactos de las capas, la transformación de coordenadas y el tratamiento de NoData. Las comprobaciones del paquete se conservan como resultados reportados en el borrador; quedan pendientes de reproducción por el equipo.

### 14. Fuentes y trazabilidad

- **[L] Luzzi et al. (2025).** *Geomorphological Evidence of Near-Surface Ice at Candidate Landing Sites in Northern Amazonis Planitia, Mars*. [DOI](https://doi.org/10.1029/2024JE008724). Las páginas citadas corresponden a las 38 páginas del PDF.
- **[Q] Anglés, A. y Li, Y. (2017).** *The western Qaidam Basin as a potential Martian environmental analogue: An overview*. [DOI](https://doi.org/10.1002/2017JE005293).
- **[S] Paquete SWIM aportado.** `SWIMProducts.zip`. Los README solicitan citar Morgan, G. A., Putzig, N. E. y colaboradores (2025), *Refined Mapping of Subsurface Water Ice on Mars to Support Future Missions*, Planetary Science Journal, 6, 29, [DOI](https://doi.org/10.3847/PSJ/ad9b24). El inventario y las comprobaciones descritas proceden de los archivos aportados; no implican revisión completa de ese artículo metodológico.
- **[N] Notas de trabajo.** `MARTE 2026 .docx` (archivo de trabajo del equipo).
- **Contexto previo.** [NASA, 26 de octubre de 2023: cartografía del hielo marciano](https://www.nasa.gov/solar-system/planets/mars/nasa-is-locating-ice-on-mars-with-this-new-map/) y [portal SWIM](https://swim.psi.edu/).
- **Documento anterior.** [Investigacion_Marte_requisitos_para_analogos.md](Estado%20del%20arte/Investigacion_Marte_requisitos_para_analogos.md).

#### Fuentes añadidas para la caracterización regional

Consulta bibliográfica: 14 de noviembre de 2026. Se indican los tipos de evidencia; un resumen de congreso tiene menor desarrollo metodológico que un artículo completo. No se descargaron nuevos raster climáticos ni se ejecutaron simulaciones.

- **[R1] Ramsdale et al. (2019).** *Grid Mapping the Northern Plains of Mars: Geomorphological, Radar, and Water-Equivalent Hydrogen Results From Arcadia Plantia*. JGR: Planets, 124, 504–527. [DOI: 10.1029/2018JE005663](https://doi.org/10.1029/2018JE005663). Cartografía regional y comparación de geomorfología, radar e hidrógeno; la franja estudiada no coincide con las huellas AP.
- **[R2] Hibbard et al. (2018).** *Evidence for Flow in Buried Ice in the Mid-Latitudes of Arcadia Planitia*. LPSC, resumen 2606. [PDF, 2 páginas](https://www.hou.usra.edu/meetings/lpsc2018/pdf/2606.pdf). Fuente de los intervalos de inercia térmica y de las inferencias sobre partículas superficiales. Resultados preliminares de congreso; no mediciones geotécnicas.
- **[R3] Hibbard, Williams, Golombek, Osinski y Godin (2021).** *Evidence for widespread glaciation in Arcadia Planitia, Mars*. Icarus, 359, 114298; edición del 1 de mayo de 2021. [DOI: 10.1016/j.icarus.2020.114298](https://doi.org/10.1016/j.icarus.2020.114298). Se verificaron resumen y metadatos accesibles; no se realizó revisión integral del texto cerrado. Interpretación de las unidades sinuosas a partir de varios conjuntos orbitales.
- **[R4] Bramson, Byrne y Bapst (2017).** *Preservation of Midlatitude Ice Sheets on Mars*. JGR: Planets, 122, 2250–2266; primera publicación el 11 de octubre de 2017. [DOI: 10.1002/2017JE005357](https://doi.org/10.1002/2017JE005357). Tabla 1 y secciones de introducción/modelado: propiedades representativas, espesor interpretado y preservación. Antecedente radar: Bramson et al. (2015), [Widespread excess ice in Arcadia Planitia, Mars](https://doi.org/10.1002/2015GL064844).
- **[R5] Campbell y Morgan (2018).** *Fine-Scale Layering of Mars Polar Deposits and Signatures of Ice Content in Nonpolar Material From Multiband SHARAD Data Processing*. GRL. [DOI: 10.1002/2017GL075844](https://doi.org/10.1002/2017GL075844). Atenuación radar: interpretación alternativa a depósitos dominados por hielo en todo su espesor.
- **[R6] Piqueux et al. (2019).** *Widespread Shallow Water Ice on Mars at High Latitudes and Midlatitudes*. GRL, 46, 14290–14298. [DOI: 10.1029/2019GL083947](https://doi.org/10.1029/2019GL083947). Temperaturas MCS/THEMIS y ajuste de dos capas; producto regional de 3 píxeles por grado.
- **[R7] Golombek et al. (2021).** *SpaceX Starship Landing Sites on Mars*. LPSC, resumen 2420. [PDF, 2 páginas](https://www.hou.usra.edu/meetings/lpsc2021/pdf/2420.pdf). Tabla 1: elevaciones; texto: criterios y superficies evaluadas. Estudio de candidatos, no designación vigente de una base ni certificación de aterrizaje.
- **[R8] Heavens (2017).** *Textured Dust Storm Activity in Northeast Amazonis–Southwest Arcadia, Mars: Phenomenology and Dynamical Interpretation*. Journal of the Atmospheric Sciences, 74, 1011–1037, abril de 2017. [DOI: 10.1175/JAS-D-16-0211.1](https://doi.org/10.1175/JAS-D-16-0211.1). Observación y análisis de tormentas regionales; no serie meteorológica en los AP.
- **[R9] Stanzel et al. (2006).** *Dust devils on Mars observed by the High Resolution Stereo Camera*. GRL. [DOI: 10.1029/2006GL025816](https://doi.org/10.1029/2006GL025816). Detección de remolinos activos, incluida Arcadia.
- **[R10] NASA/NSSDC.** [Mars Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/marsfact.html). Contexto planetario; no observaciones locales de Arcadia.
- **[R11] Equipo Mars Climate Database.** [Documentación del acceso web](https://www-mars.lmd.jussieu.fr/mars/info_web/) y [descripción de MCD 6.1, 2022](https://meetingorganizer.copernicus.org/EPSC2022/EPSC2022-786.html). Modelos, variables y escenarios; registrar la versión realmente utilizada al generar una salida.
- **[R12] Equipo LMD.** [Climatologies of the Martian Atmospheric Dust Optical Depth](https://www-mars.lmd.jussieu.fr/mars/dust_climatology/). Productos de opacidad y normalizaciones; acceso identificado, sin extracción espacial en esta revisión.
- **[R13] Courville et al. (2026).** *Subsurface Water Ice Mapping on Mars: A Probabilistic Approach*. Planetary Science Journal, 7, 183. [DOI: 10.3847/PSJ/ae8904](https://doi.org/10.3847/PSJ/ae8904); [registro institucional USGS](https://pubs.usgs.gov/publication/70279509). Publicación registrada el 31 de julio de 2026. Marco probabilístico posterior a los productos citados en la sección 7; no se recalcularon los valores anteriores.

---

## AP-1: caracterización para buscar análogos terrestres

**Proyecto:** NASA Space Apps 2026 · **Responsable:** línea Marte, Matías  
**Fecha:** 14 de noviembre de 2026 · **Referencia:** Arcadia–Amazonis  
**Estado:** ficha documental que cubre todas las dimensiones del XMind. No equivale a una caracterización instrumental completa: los campos sin respaldo local se mantienen explícitamente abiertos.

### 1. Identidad, delimitación e interés

AP-1 es un candidato de aterrizaje estudiado en la transición entre Arcadia y Amazonis septentrional, sobre una unidad sinuosa interpretada como relacionada con hielo. Su interés combina terreno relativamente poco accidentado e indicios de hielo subsuperficial. La evaluación publicada favorece su seguridad relativa entre los candidatos analizados; no certifica una base futura ni elimina riesgos. [1, 4]

| Campo | Valor y alcance |
|---|---|
| Coordenada nominal | 39,8° N; 202,1° E, equivalente a −157,9° |
| Elevación publicada | Aproximadamente −3,9 km respecto al geoide MOLA [4] |
| Unidad geomorfológica | Unidad sinuosa; no asumir que toda su extensión comparte iguales propiedades [1] |
| Área caracterizada en el artículo | Huella de la imagen HiRISE; no una elipse de aterrizaje |
| Límite operativo para comparar análogos | Aún debe definirse; el punto nominal no delimita un área |
| Finalidad de esta ficha | Referencia para ensayos de terreno, hielo y operaciones; no diseño de una base |

### 2. Observaciones identificadas y trazabilidad

Se verificaron las fichas oficiales del par estéreo de NASA/MRO/HiRISE. Los centros de imagen difieren ligeramente del punto nominal: no son coordenadas alternativas del sitio. [2, 3]

| Metadato | ESP_052424_2200 | ESP_052490_2200 |
|---|---|---|
| Fecha de adquisición | 2 octubre 2017 | 7 octubre 2017 |
| Hora local marciana | 14:49 | 14:59 |
| Centro | 39,806° N; 202,080° E | 39,809° N; 202,081° E |
| Escala original | 30,0 cm/píxel | 31,8 cm/píxel |
| Escala proyectada | 25 cm/píxel | 25 cm/píxel |
| Longitud solar Ls | 68,7° | 70,9° |
| Estación | Primavera boreal | Primavera boreal |
| Incidencia solar | 39° | 41° |
| Emisión | 2,0° | 20,6° |

El remuestreo a 25 cm no crea resolución nueva. Dos escenas vespertinas de primavera no describen el ciclo diario o anual. Los colores de HiRISE no sustituyen una identificación mineralógica espectral.

Luzzi et al. procesaron datos EDR con ISIS y Ames Stereo Pipeline, ajustaron la topografía usando MOLA o HRSC según disponibilidad y elaboraron cartografía geomorfológica. Sus resultados publicados se reutilizan aquí: no se recalcularon sus DEM ni se descargaron los JP2 completos en esta entrega. [1, pp. 5–6]

### 3. Relieve superficial, pendiente y movilidad

| Propiedad | Resultado para el área AP-1 | Interpretación y límite |
|---|---|---|
| Desnivel máximo | 31 m en la huella HiRISE [1, p. 5] | No es pendiente ni rugosidad a escala de rueda |
| Polígonos | Diámetro modal 11,7 m; desviación estándar 3,3 m [1, p. 15] | Moda y dispersión; no rango mínimo–máximo |
| Cráteres expandidos | Identificados | Relieve relacionado con modificación posterior al impacto |
| Cráteres expandidos invertidos | Identificados | Inversión del relieve; exige examinar crestas y depresiones |
| Formas semejantes a pingos | Identificadas | Clasificación morfológica; no prueba de agua líquida actual |
| Terreno «brain coral» | Identificado | Superficie de crestas y surcos; su parecido no demuestra un mecanismo único |
| Crestas arqueadas | Identificadas | Elementos relevantes para recorridos y contraste de procesos |
| Pendiente, percentiles y escala de cálculo | Sin estadística local homogénea incorporada | No convertir 31 m de desnivel en grados |
| Abundancia y altura de bloques | Sin inventario cuantitativo incorporado | No interpretar «relativamente seguro» como ausencia de obstáculos |

Presencias: tabla 2 de [1]. Las alturas poligonales del documento regional proceden de una muestra conjunta de los tres sitios; no se importan como distribución exclusiva de AP-1.

**Consecuencia para análogos:** interesa una combinación de llanura y microrelieve poligonal, no únicamente un paisaje plano. La pendiente, rugosidad y obstáculos deben compararse a escalas equivalentes.

### 4. Materiales, mineralogía y geología

AP-1 pertenece a una unidad cuya interpretación regional incluye hielo enterrado y cobertura detrítica. La cartografía local documenta formas y relaciones espaciales, no una composición química completa. [1]

| Pregunta del XMind | Resultado defendible |
|---|---|
| ¿Basaltos y materiales volcánicos? | Hay contexto volcánico regional, pero no se identificó aquí una composición basáltica cuantitativa de la cobertura de AP-1 |
| ¿Arcillas? | Sin identificación local confirmada en los productos revisados |
| ¿Sulfatos, sales o percloratos? | Sin especies, concentraciones o mapas locales verificados |
| ¿Granulometría? | No se dispone de distribución medida de tamaños; las inferencias térmicas regionales no la sustituyen |
| ¿Canales y deltas? | No se estableció un sistema fluvial-deltaico local en esta ficha; no confundir una unidad sinuosa interpretada como glacial con un cauce |
| ¿Dunas y formas eólicas? | No se incorporó un inventario local de dimensiones, migración y actividad |
| ¿Terreno poligonal? | Sí, con tamaño modal cuantificado; interpretación asociada a contracción térmica y evolución de terreno con hielo |
| ¿Alteración y secuencia temporal? | Las formas indican una historia de modificación; no hay una edad absoluta única verificada para toda el área |

«Sin identificación» describe nuestra evidencia, no una ausencia demostrada. Se necesitan productos espectrales con cobertura verificada, calidad suficiente y análisis de bandas antes de seleccionar un análogo mineralógico.

### 5. Agua, hielo, sales y cantidad

La evidencia local más desarrollada es geomorfológica. La exposición de hielo en un impacto cercano aporta evidencia adicional, pero ocurre aproximadamente a 23 km de AP-1. [1]

| Variable | Evidencia | Lo que no demuestra |
|---|---|---|
| Presencia de procesos relacionados con hielo | Polígonos y otras formas descritas | Contenido actual en cada punto |
| Profundidad de unos 8–12 cm inferida mediante polígonos | Estimación asociada a la formación del patrón | Profundidad actual confirmada bajo AP-1 |
| Hielo expuesto a 50–60 cm bajo el borde máximo de un cráter cercano | Observación fuera del sitio nominal | Profundidad previa al impacto ni una perforación en AP-1 |
| Espesor de hielo | No cuantificado de manera local concluyente aquí | No adoptar automáticamente los 30–80 m regionales |
| Pureza, porosidad y continuidad | No medidas directamente bajo AP-1 en esta revisión | No derivarlas del índice SWIM |
| Agua líquida actual | No establecida | La presencia de hielo no basta |
| Agua antigua | Interpretación de procesos criogénicos; no prueba de un lago local | No convertir cualquier forma degradada en evidencia de agua líquida |
| Sales y salmueras | Sin caracterización local | No atribuir a AP-1 resultados de Phoenix |

Valores de AP-1 transcritos de la tabla 3 de [1]:

| Índice SWIM | Valor |
|---|---:|
| Combinado 0–1 m | 0,20 |
| Geomorfología | 0,63 |
| Neutrones | 0,29 |
| Potencia radar superficial | 0 |
| Térmico | 0 |
| Propiedades dieléctricas estimadas | 0,10 |

Son índices de consistencia, no probabilidades ni fracciones de hielo. Un cero no prueba ausencia de hielo. La versión y método deben conservarse al comparar con productos posteriores.

En el ZIP SWIM aportado, el píxel regional del punto AP-1 tiene valor 1 en cráteres expandidos, manto dependiente de latitud y terreno texturado; valor 0 en terreno festoneado y cráteres aterrazados. La inspección previa encontró píxeles de unos 3 km: no son inventarios de objetos individuales ni porcentajes de cobertura.

### 6. Temperatura, iluminación y ambiente

| Campo solicitado | Estado específico de AP-1 | Información necesaria |
|---|---|---|
| Temperatura del suelo durante el día | Sin serie extraída | Temperatura de superficie, hora local, fecha y calidad |
| Temperatura del aire | Sin serie local incorporada | Altura sobre suelo y método de observación/modelado |
| Ciclo diario | No reconstruido | Muestreo de horas o modelo validado |
| Ciclo estacional | No reconstruido | Ls y años marcianos; separar variación interanual |
| Temperatura subsuperficial | No medida aquí | Profundidad y propiedades térmicas de las capas |
| Iluminación | Geometría solar conocida en las dos escenas [2, 3] | Modelo de horizonte para duración estacional y sombras |
| Inercia térmica | No se extrajo un valor exclusivo de AP-1 | Producto térmico y estadística dentro del polígono |
| Radiación ionizante | Sin dosis local verificada | Modelo de transporte, profundidad, atmósfera y actividad solar |
| UV | Sin flujo local verificado | Espectro, hora, polvo y geometría solar |

No se importan como medidas de AP-1 los intervalos térmicos de las unidades regionales. Para cubrir cuantitativamente el ambiente se requieren MCS/THEMIS o salidas de un modelo como MCD, etiquetadas como modeladas. Esta entrega no ejecutó MCD; no presenta números simulados como si fueran observaciones.

### 7. Atmósfera, viento y polvo

El contexto de Marte es una atmósfera tenue dominada por CO₂. La presión media planetaria no es una medida de AP-1. Su elevación debe entrar en cualquier estimación local. [8]

Se ha documentado actividad eólica y de polvo en Arcadia–Amazonis, pero no se ha obtenido aquí una climatología específica del polígono AP-1. Por tanto:

- **Presión:** sin rango local y estacional validado en esta ficha.
- **Composición:** contexto marciano; sin medición química atmosférica local.
- **Viento:** faltan velocidad, dirección, altura y distribución de ráfagas.
- **Tormentas:** no se asigna frecuencia anual a partir de ejemplos regionales.
- **Polvo suspendido:** falta serie de opacidad con longitud de onda y fechas.
- **Polvo depositado:** sin tasa local de acumulación o retirada sobre equipos.

La comparación terrestre no debe usar únicamente velocidad del viento: la interacción con partículas depende también de densidad atmosférica, gravedad, tamaño de grano y cohesión. Esta es una limitación física de la analogía, no un motivo para descartar ensayos de navegación o mantenimiento en campo.

### 8. Actividad geológica, erosión, cuevas y subsuelo

La cartografía sustenta estudiar contracción térmica, evolución de formas relacionadas con hielo, impactos y posible pérdida por sublimación. La interpretación de una forma antigua no prueba que el proceso siga activo a la misma tasa. [1]

No se establecieron para AP-1 erupciones actuales, flujo de lava activo, cuevas accesibles o tubos de lava. Tampoco se cuantificaron tasas actuales de erosión, sublimación o movimiento del terreno. Para demostrar cambio se necesitan imágenes repetidas registradas entre sí, con diferencias de iluminación controladas. El par estéreo de 2017 se usa principalmente para geometría, no como demostración de evolución.

### 9. Mecánica del terreno y condiciones operativas

No se dispone aquí de mediciones locales de cohesión, fricción, densidad aparente, resistencia portante, compactación, abrasividad o carga electrostática. La pendiente favorable no garantiza soporte ni perforabilidad.

| Operación | Lo que aporta AP-1 | Límite para un ensayo análogo |
|---|---|---|
| Movilidad y navegación | Terreno poligonal, crestas, cráteres y bajo relieve general | Necesita estadísticas comparables de obstáculos y pendientes |
| Prospección del hielo | Evidencia heterogénea y discrepancia de escalas | Útil para ensayar cómo combinar instrumentos, no para suponer un depósito uniforme |
| Perforación/excavación | Objetivo plausible de investigar cobertura y hielo | No hay profundidad/resistencia local suficiente para fijar una especificación única |
| Construcción | Interés en soporte y preparación de superficie | No existe validación geotécnica local en esta ficha |
| Energía | Polvo, iluminación y temperatura son relevantes | No se calculó rendimiento fotovoltaico ni balance energético |
| Comunicaciones y EVA | El terreno permite plantear recorridos | No se calcularon enlaces, cobertura orbital ni seguridad de EVA |
| Factores humanos | Puede inspirar tareas y restricciones operativas | Aislamiento y confinamiento son propiedades del diseño de la misión terrestre |

### 10. Astrobiología: cuatro preguntas separadas

| Dimensión del XMind | Evaluación |
|---|---|
| Habitabilidad | Hielo por sí solo no prueba agua líquida disponible, energía o condiciones favorables para vida |
| Preservación | El subsuelo es una hipótesis de interés; no se cuantificó preservación de orgánicos en AP-1 |
| Detectabilidad | Dependerá de instrumento, profundidad, matriz y límite de detección; no está demostrada |
| Origen biológico | No se identificó una biosignatura confirmada en la evidencia revisada |

No se elige un sitio terrestre «con extremófilos» como equivalente de AP-1 sin definir qué hipótesis se quiere probar. Un análogo de proceso o de muestreo puede ser útil aunque no reproduzca habitabilidad marciana.

### 11. Uso del terreno, permisos y localización terrestre

Este campo del XMind corresponde al candidato terrestre, no al punto marciano. Para AP-1 se registra **no aplicable** en permisos de acceso terrestre, propietario, área protegida, servicios cercanos y temporada de visita. Se completará para cada análogo, sin confundir facilidad logística con fidelidad científica.

### 12. Cómo se utilizan los repositorios aportados

| Repositorio | Papel en esta ficha o etapa posterior | Estado de uso |
|---|---|---|
| NASA PDS / HiRISE | Productos y geometría orbital de AP-1 | Par exacto verificado [2, 3, 5] |
| NASA PDS / ODE | Búsqueda cruzada de CRISM, CTX, SHARAD, MCS y HiRISE | Capacidades verificadas; no se verificó cobertura local de cada instrumento [5] |
| ESA Mars Express / HRSC | Contexto topográfico y apoyo a DEM, según disponibilidad | Uso descrito en el artículo; sin identificador HRSC local confirmado [1, 6] |
| ESA PSA | Archivo planetario complementario | Acceso web bloqueado en esta revisión; no se afirma descarga de datos |
| NASA Earthdata / Worldview | Caracterización y exploración visual de candidatos terrestres | No son observaciones de AP-1 |
| Copernicus Data Space | Datos Sentinel de candidatos terrestres | Función terrestre verificada [7] |
| JAXA G-Portal | Observaciones terrestres para candidatos | Función terrestre verificada [7] |
| CSA RADARSAT | Radar para candidatos terrestres | Recurso aportado; no utilizado para medir AP-1 |
| LRO / Diviner | Referencias lunares | No corresponde al sitio marciano |

No se necesita utilizar todas las agencias para cada sitio. Se necesita una fuente adecuada para cada variable, con cobertura, resolución y calidad verificadas.

### 13. Perfil provisional para buscar análogos

Esta es una propuesta derivada de la evidencia, no un ranking validado:

**AP-1 representa principalmente un terreno de llanura con microrelieve poligonal y otras formas vinculadas a hielo subsuperficial, cuya profundidad y propiedades locales siguen siendo inciertas.**

| Objetivo del ensayo | Qué buscar en la Tierra | Qué no exigir sin evidencia |
|---|---|---|
| Interpretar procesos criogénicos | Polígonos, terreno con hielo y documentación del mecanismo de formación | Que cualquier patrón poligonal tenga el mismo origen |
| Navegar y muestrear | Geometría de obstáculos comparable, recorridos y cartografía detallada | Igual elevación absoluta respecto al nivel terrestre |
| Detectar hielo enterrado | Cobertura superficial y hielo cuya profundidad pueda medirse de forma independiente | Hielo exactamente a 10 cm por una inferencia marciana histórica |
| Ensayar excavación | Materiales y hielo caracterizados mecánicamente | Igualdad geotécnica aún no demostrada con AP-1 |
| Trabajar con polvo | Partículas y tareas medibles | Reproducir al aire libre la dinámica atmosférica marciana completa |

### 14. Estado final y trabajos que todavía hacen falta

La ficha cubre todas las preguntas del XMind, pero **no todos sus parámetros pueden darse por caracterizados cuantitativamente**. El soporte más fuerte es topográfico, geomorfológico y documental sobre hielo.

Para cerrar los campos restantes hacen falta: un polígono de análisis común; extracción de pendientes y obstáculos del DEM; consulta de cobertura espectral y análisis mineralógico; series térmicas; modelado atmosférico explícito; y, para propiedades geotécnicas profundas, evidencia que probablemente requiera nuevas mediciones. No se declara completado ese procesamiento.

Corrección del XMind: las descripciones de Jezero y Oxia están intercambiadas. La referencia a Rosalind Franklin corresponde a Oxia Planum; Jezero es la referencia de Perseverance y del sistema fluvial-lacustre. Esta corrección no cambia la presente ficha de AP-1.

### Fuentes

1. **Luzzi et al., 2025.** *Geomorphological Evidence of Near-Surface Ice at Candidate Landing Sites in Northern Amazonis Planitia, Mars*. [DOI](https://doi.org/10.1029/2024JE008724). PDF aportado, 38 páginas; especialmente pp. 5–6, 15–19, 25–26 y 32–33. Fuente de mediciones y clasificaciones locales; no nuevas mediciones nuestras.
2. **NASA/JPL-Caltech/UArizona, HiRISE.** [ESP_052424_2200](https://hirise.lpl.arizona.edu/ESP_052424_2200). Ficha oficial y enlaces a productos PDS.
3. **NASA/JPL-Caltech/UArizona, HiRISE.** [ESP_052490_2200](https://hirise.lpl.arizona.edu/ESP_052490_2200). Ficha oficial y enlaces a productos PDS.
4. **Golombek et al., 2021.** *SpaceX Starship Landing Sites on Mars*, LPSC 2420. [PDF](https://www.hou.usra.edu/meetings/lpsc2021/pdf/2420.pdf). Evaluación histórica de candidatos, tabla 1 y texto; no anuncio de una selección actual.
5. **NASA PDS Geosciences.** [Datos MRO](https://pds-geosciences.wustl.edu/missions/mro/default.htm) y [ODE](https://ode.rsl.wustl.edu/). Catálogos; su disponibilidad no confirma por sí sola cobertura útil de AP-1.
6. **ESA/DLR, HRSC.** [Documento de archivo HRSC](https://archives.esac.esa.int/psa/ftp/MARS-EXPRESS/HRSC/MEX-M-HRSC-4-REFDR-MAPPROJECT-EXT3-V4.0/DOCUMENT/HRSC_EAICD.PDF). Fuente de documentación del archivo; no un producto local extraído.
7. **Portales terrestres:** [JAXA G-Portal](https://gportal.jaxa.jp/), [Copernicus Explore Data](https://dataspace.copernicus.eu/explore-data), [NASA Earthdata](https://search.earthdata.nasa.gov/) y [Worldview](https://worldview.earthdata.nasa.gov/). Los dos últimos fueron aportados por el equipo; no se extrajeron datos terrestres en esta ficha.
8. **NASA/NSSDC.** [Mars Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/marsfact.html). Contexto planetario; no medición de AP-1.
9. **Documento de continuidad:** `Arcadia_Amazonis_consolidacion_de_evidencia.md`, versión ampliada del 14/11/2026. Contiene la revisión regional y la inspección reproducible del ZIP SWIM aportado. Los resultados regionales no se transfieren automáticamente a AP-1.
