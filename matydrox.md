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

---

## Tres regiones marcianas para la búsqueda de análogos terrestres: Jezero, Gale y Oxia Planum

**NASA Space Apps Challenge 2026 · Línea Marte**  
**Fecha:** 14 de noviembre de 2026  
**Alcance:** caracterización **regional**; las características de una roca, perforación, punto del recorrido o elipse no se atribuyen a toda la región. Complementa las fichas de Arcadia y AP-1.

### 1. Cómo interpretar las tres regiones

Jezero sirve principalmente para comparar una cuenca de impacto con registro fluvial y lacustre, un delta y materiales ígneos alterados; Gale, una larga sucesión de ambientes lacustres, eólicos y de alteración leída por un rover; Oxia, una extensa planicie antigua con arcillas cartografiadas desde órbita, relieves fluviales y la futura exploración subsuperficial de Rosalind Franklin. Son **referencias para distintas actividades análogas**, no tres aspirantes equivalentes a una base permanente. [J1, G1, O1]

| Región | Unidad de estudio | Dato directo de superficie | Principal incertidumbre de escala |
|---|---|---|---|
| Jezero | Cráter ~45 km, cuenca de captación, delta occidental, piso y margen | Perseverance desde febrero de 2021 | El corredor visitado no representa todos los sedimentos de la cuenca [J2, J3] |
| Gale | Cráter ~154 km, piso y estratos de Aeolis Mons / Mount Sharp | Curiosity desde agosto de 2012 | La sección recorrida muestrea algunas unidades del enorme edificio sedimentario [G1] |
| Oxia Planum | Llanura en el borde oriental de Chryse, cerca de 18° N; zona cartografiada para aterrizaje | Sin rover en superficie a esta fecha | Mineralogía, procesos y accesibilidad se infieren principalmente de órbita [O1, O2] |

**Corrección del XMind:** Perseverance explora Jezero; la selección de Rosalind Franklin corresponde a Oxia. Gale es el lugar de Curiosity. [J2, G1, O1]

### 2. Jezero: cuenca de impacto, delta y rocas ígneas

#### 2.1 Paisaje y secuencia

Jezero es un cráter con antiguos valles de entrada, abanico/delta occidental, piso y bordes. La geometría sedimentaria vista desde órbita y desde Perseverance respalda transporte fluvial hacia un antiguo cuerpo de agua. La distribución de rocas cambia entre el piso, el abanico y la unidad marginal. Seleccionar un solo paisaje terrestre para «todo Jezero» perdería esa diversidad. [J2–J5]

El aterrizaje de Perseverance en el piso ocurrió el 18 de febrero de 2021. Una elipse publicada de **7,7 × 6,6 km** es información histórica de esa misión, no el límite del cráter. El delta se investigó después del piso. [J2, J3]

#### 2.2 Materiales, mineralogía, agua y sales

Las primeras mediciones de SuperCam en el piso encontraron rocas con olivino y piroxenos; el miembro inferior Séítah incluye acumulación ígnea de granos milimétricos de olivino, mientras unidades superiores muestran otras composiciones. La evidencia de alteración por fluidos está presente, pero es espacialmente variable. **El piso no puede clasificarse sencillamente como fondo lacustre sedimentario** por su aspecto en imágenes orbitales. [J4, J5]

En el abanico superior, análisis de SHERLOC de siete objetivos erosionados identificaron, entre otros, carbonatos, sulfatos y fases interpretadas como perclorato o fosfato. Ese muestreo documenta diversidad química en los objetivos medidos; no proporciona una abundancia uniforme de sales para el cráter. La interpretación del origen de los carbonatos incluye precipitación y transporte, entre otras posibilidades. [J6]

El margen añade otra secuencia posible de interacción roca–fluido: un estudio de SuperCam publicado en 2026 identifica rocas cristalinas ricas en olivino y, a menor elevación en los afloramientos examinados, señales de circulación de fluidos, carbonatos, sílice y vetas tardías. Las relaciones se han documentado en exposiciones específicas; no deben extrapolarse a todas las orillas de un paleolago. [J7]

| Pregunta | Caracterización regional de Jezero | Límite |
|---|---|---|
| Basaltos/rocas ígneas | Dominan partes del piso recorrido; unidades diferenciadas | El delta y el margen no son iguales al piso |
| Arcillas | Hay fases de alteración y contexto mineralógico de la cuenca; identificación dependiente de unidad | Sin porcentaje único regional |
| Carbonatos | Detectados en contextos marginales y abanico | Su presencia no prueba por sí sola un biomarcador |
| Sulfatos/percloratos | Detectados en algunas muestras estudiadas | Abundancia y distribución regional heterogéneas |
| Agua antigua | Red de entrada, depósito deltaico y alteración | No implica un lago permanente en todos los períodos |
| Hielo actual | No se ha establecido un reservorio somero comparable a Arcadia en esta síntesis | No convertir pasado lacustre en hielo accesible actual |
| Dunas y polvo | Sedimentos móviles y cobertura de polvo en partes del cráter | Faltan métricas regionales homogéneas de movilidad |

#### 2.3 Atmósfera, temperatura, radiación y procesos activos

El instrumento **MEDA** de Perseverance mide condiciones ambientales en su recorrido. Un análisis de **700 soles** cubre aproximadamente un año marciano de temperatura superficial y del aire próximo al suelo: documenta oscilaciones diarias y estacionales, además de variación entre soles. Son datos de un vehículo en movimiento y requieren coordenada, hora, estación, altura y período para cualquier comparación cuantitativa. No se propone un único máximo/mínimo «de Jezero» sin especificarlos. [J8]

La atmósfera marciana está dominada por CO₂, con baja presión. Jezero tiene polvo, viento y procesos eólicos; las series de MEDA pueden distinguir temperatura, presión y polvo si se extraen. La dosis de radiación, una propiedad física del entorno marciano, no queda reproducida por una cuenca terrestre visualmente similar. No se ha demostrado actividad volcánica actual ni cuevas accesibles en el conjunto de esta caracterización. [J8, M1]

#### 2.4 Astrobiología y utilidad para análogos

Un delta, sedimentos finos, rocas alteradas y carbonatos justifican investigar **preservación y detectabilidad** de posibles señales antiguas. Un compuesto orgánico, una textura sugerente o una reacción mineral no bastan por sí solos para demostrar vida; se necesitan controles de origen no biológico y contexto estratigráfico. Conviene buscar análogos por tareas: formación de delta, preservación en arcillas/carbonatos, discriminación de rocas ígneas frente a sedimentarias y estrategias de selección de muestras. [J3–J7]

### 3. Gale: una sucesión de ambientes, no un solo desierto

#### 3.1 Geografía y relieve

Gale es un cráter de impacto con una montaña sedimentaria central, Aeolis Mons (Mount Sharp). Curiosity aterrizó en agosto de 2012, exploró el piso y ascendió estratos de la base de la montaña. La altura de Mount Sharp se suele resumir como **~5 km**; esa cifra describe el edificio, no una pendiente caminable ni la elevación de cada estación de muestreo. Los estratos expuestos permiten examinar cambios de ambientes a lo largo del tiempo. [G1, G2]

No se asigna un solo valor de rugosidad a Gale: el piso con gravas, afloramientos, pendientes, crestas, dunas y laderas tienen obstáculos y escalas diferentes. Para movilidad análoga es indispensable escoger una unidad y un trayecto concreto, más el tamaño del vehículo.

#### 3.2 Rocas, minerales y agua

En Yellowknife Bay, Curiosity documentó lutitas y evidencia de un antiguo lago de agua dulce junto con componentes químicos y fuentes de energía relevantes para habitabilidad. Los estratos inferiores de Mount Sharp registran depósito lacustre y modificaciones posteriores por aguas subterráneas. Más arriba aparecen intervalos con arcillas y unidades con sulfatos; esta disposición no obliga a una historia lineal y uniforme de «lago y luego desierto». [G1, G2]

El trabajo de 2026 en la base de la unidad estratificada con sulfatos identifica una sucesión principalmente eólica de mantos arenosos y dunas, **con un intervalo lacustre y señales de humedecimiento periódico**. Otro estudio de muestras perforadas en la transición arcillas–sulfatos encuentra señales de arcillas, sulfatos de Fe/Mg y cloruros variables, interpretando fluidos salinos posteriores al depósito. Ambos muestran que unidad sedimentaria, composición y alteración se deben caracterizar por separado. [G3, G4]

| Pregunta | Caracterización regional de Gale | Límite |
|---|---|---|
| Material volcánico/basáltico | Forma parte del contexto y de sedimentos derivados | No llamar basalto a todos los estratos sedimentarios |
| Arcillas | Documentadas en intervalos y muestras | Variación vertical y lateral |
| Sulfatos y otras sales | Documentados en unidades altas y alteración diagenética | No equivalen necesariamente a un desierto totalmente seco durante cada depósito |
| Agua antigua | Lagos, aportes fluviales, agua subterránea e intervalos húmedos | Procesos con edades y escalas distintas |
| Dunas y erosión | Formas eólicas y estratos de origen eólico; erosión expone la montaña | Distinguir dunas activas de rocas depositadas por antiguas dunas |
| Hielo subsuperficial actual | No caracterizado aquí como recurso de base | No trasladar depósitos de Arcadia |
| Cuevas/erupciones actuales | No documentadas como rasgo de las unidades seleccionadas | No inferir ausencia absoluta en todo el cráter |

#### 3.3 Ambiente medido y biología

Curiosity tiene el instrumento meteorológico **REMS** y un conjunto de análisis de muestras a bordo (incluido SAM). Gale posee, por tanto, observaciones directas de temperatura del aire/suelo, presión, viento y condiciones de polvo en su trayecto; cualquier cifra debe venir con sol, hora local, altura y ubicación. Para la comparación con un sitio terrestre hay que distinguir clima **actual** medido del clima **antiguo** interpretado a partir de las rocas. [G1, M2]

Los hallazgos de carbono orgánico y otros compuestos en muestras examinadas se investigan en el contexto de fuentes bióticas y abióticas. La evidencia de habitabilidad antigua en varios ambientes no constituye detección de vida. La astrobiología de Gale favorece análogos de depósito, diagénesis, preservación de compuestos y decisión de dónde perforar. La radiación sobre la superficie y dentro del suelo requiere tratamiento específico y no se equipara a la de un desierto terrestre. [G1, G4]

#### 3.4 Perfil para búsqueda terrestre

Separar al menos tres tareas: **(a)** lago y lutitas antiguas, **(b)** transición mineralógica y aguas salinas, **(c)** dunas/mantos arenosos y agua fluctuante. Una sola localización terrestre podría cubrir alguna tarea, pero habrá que explicar cuáles y por qué.

### 4. Oxia Planum: arcillas antiguas y cartografía antes del aterrizaje

#### 4.1 Contexto, selección y estado de misión

Oxia se encuentra cerca de **18° N**, en el borde oriental de la cuenca de Chryse y en la transición geológica entre tierras altas y bajas. ESA mantiene la selección de esta región para **Rosalind Franklin**, con lanzamiento programado para **2028** según la ficha consultada. A noviembre de 2026 **no hay mediciones del rover en Oxia**; el calendario de una misión es información sujeta a actualización. [O1]

Su objetivo es estudiar materiales antiguos ricos en minerales arcillosos y buscar posibles señales de vida pasada. El taladro planeado puede alcanzar **hasta 2 m**: es una capacidad prevista del instrumento, no una profundidad a la que ya se haya detectado una biosignatura en Oxia. [O1]

#### 4.2 Cartografía, relieve y procesos

El mapa de Fawdon et al. (2024), a escala **1:30.000**, distingue **15 unidades de roca en seis grupos y siete unidades superficiales/texturales**. Combina datos visibles e infrarrojos de órbita y plantea relaciones entre afloramientos, depósitos y superficies que guían la futura selección de muestras. Es una interpretación previa al trabajo de campo marciano. [O2]

Un estudio de crestas sinuosas con HiRISE, CTX y **CaSSIS** de ESA interpreta parte de las rocas portadoras de filosilicatos como depósitos de antiguos sistemas fluviales/aluviales. La forma sinuosa por sí sola puede tener diversas causas: la inferencia combina relieve, geometría y contexto. No se debe imponer a todas las unidades arcillosas una misma historia fluvial. [O3]

| Pregunta | Caracterización regional de Oxia | Límite |
|---|---|---|
| Relieve superficial | Llanura con diversidad de unidades, crestas y afloramientos mapeados | Sin estadística homogénea de pendientes/obstáculos en este documento |
| Arcillas | Exposiciones extensas de filosilicatos asociadas a agua antigua | Mineral específico y abundancia dependen del afloramiento y espectro |
| Basaltos y rocas volcánicas | No se asigna composición volcánica a todos los mantos oscuros | Requiere análisis mineralógico de cada unidad |
| Sulfatos, carbonatos, percloratos | No hay en esta síntesis cuantificación regional demostrada | Evitar transferir hallazgos de Jezero o Gale |
| Agua antigua | Alteración mineral y evidencia de antiguos depósitos fluviales | No demuestra agua líquida presente hoy |
| Hielo actual / cantidad | Sin reservorio local cuantificado aquí | No confundir taladro de 2 m con detección de hielo |
| Dunas, polvo, erosión | Unidades superficiales cartografiadas y procesos de modificación | Faltan tasas y validación local de superficies activas |
| Erupciones/cuevas | Sin evidencia particular incorporada para ensayos de esos procesos | No atribuir capacidades de «análogo volcánico» sin unidad concreta |

#### 4.3 Atmósfera, temperatura, radiación y astrobiología

La presión, temperaturas diarias/estacionales, viento y polvo de Oxia **no se han medido por un vehículo en la región**. Productos orbitales o una Mars Climate Database pueden suministrar observaciones/modelos según cobertura, hora, elevación y escenario de polvo. Hay que rotular qué tipo de dato se extrajo; en este documento no se ejecutó un modelo de clima local. [M1, M3]

La hipótesis astrobiológica combina rocas antiguas, arcillas, exposición y acceso por perforación. Las arcillas pueden registrar interacciones pasadas con agua, pero su sola presencia no demuestra preservación de compuestos orgánicos ni origen biológico. Hasta que Rosalind Franklin analice muestras, **habitabilidad, preservación, detectabilidad y vida** son preguntas separadas. [O1, O2]

#### 4.4 Perfil para búsqueda terrestre

Buscar afloramientos de depósitos fluviales antiguos con filosilicatos medidos, relaciones estratigráficas legibles y posibilidad real de muestreo bajo cobertura superficial. Los terrenos elegidos deberán conservar permisos, accesibilidad y restricciones ambientales documentados. Análogos de salares muy recientes podrían reproducir ciertas sales, pero no automáticamente el proceso que produjo las arcillas antiguas de Oxia.

### 5. Comparación transversal para el futuro catálogo

| Criterio del XMind | Jezero | Gale | Oxia |
|---|---|---|---|
| Proceso central | Entrada fluvial, abanico/delta y alteración de piso/margen | Acumulación, erosión y diagénesis de una extensa secuencia | Alteración antigua y depósitos fluviales/planicie arcillosa |
| Geología decisiva | Ígneo + delta + carbonatos en contextos distintos | Lutitas, arcillas, sales y arenas estratificadas | Unidades con filosilicatos cartografiadas desde órbita |
| Mejor tipo de análogo | Lago-delta con mineralogía y estratos estudiados | Sucesión lacustre–eólica con alteración posterior | Llanura fluvial antigua arcillosa y test de muestreo subsuperficial |
| Evidencia de campo marciano | Perseverance | Curiosity | Aún no |
| Ambiente actual | MEDA a lo largo de recorrido | REMS a lo largo de recorrido | Orbital/modelado si se extrae |
| Hielo superficial como recurso | No establecido aquí | No establecido aquí | No establecido aquí |
| Biosignatura confirmada | No | No | No hay exploración in situ todavía |
| Riesgo para el comparador | Equiparar todo el piso con delta | Reducir una historia compleja a una transición seca simple | Tratar un mapa predictivo como verificación en superficie |

La selección del análogo debe arrancar por una **pregunta ensayable**: por ejemplo, identificar sedimentos deltaicos, buscar orgánicos en filosilicatos, distinguir diagénesis salina de depósito primario o planear una perforación. Luego se ponderan propiedades que sí importan para esa tarea. Una apariencia similar en imagen satelital es solo una pista.

### 6. Cómo se conectan las bibliotecas NASA, ESA, JAXA y CSA

| Biblioteca | Uso apropiado | Aplicación en este informe |
|---|---|---|
| NASA PDS / ODE | MRO: CRISM, HiRISE, CTX, MCS, SHARAD; catálogos planetarios | Verificar cobertura y descargar productos para polígonos de cada región [D1] |
| NASA Perseverance y Curiosity | Mediciones de superficie, imágenes, química y meteorología | Fundamentan Jezero y Gale; requieren selección espacial/temporal [J4, J8, M2] |
| ESA Mars Express HRSC/OMEGA y TGO CaSSIS | Topografía, imagen y mineralogía marciana según instrumento | Oxia y contexto de las demás; CaSSIS en [O3] |
| NASA Earthdata y Worldview | Tierra: temperatura, hielo, polvo y visualización | Se aplicarán a candidatos terrestres, no a coordenadas marcianas |
| ESA Copernicus Data Space | Sentinel para materiales superficiales, cubierta, relieve indirecto, cambios | Se aplicará a candidatos terrestres [D2] |
| JAXA G-Portal | Variables de observación terrestre según misión/producto | Se aplicará a candidatos terrestres [D3] |
| CSA RADARSAT | Radar terrestre con limitaciones de acceso/producto y geometría | Posible caracterización de hielo o superficie terrestre |
| NASA LRO / Diviner | Referencias lunares | Fuera de estas tres regiones marcianas |

En este informe se revisaron publicaciones y fichas oficiales; **no se descargaron nuevos productos orbitales o raster de temperatura**. La tabla indica el camino verificable para completar campos numéricos, no análisis que ya se hayan hecho.

### 7. Campos de datos que deben acompañar cada futuro análogo terrestre

- Delimitar **polígono**, tamaño y proceso que se representa; guardar latitud/longitud y fecha de observación.
- Identificar litología/mineral con método, profundidad, muestra y laboratorio; distinguir parecido geométrico de mecanismo.
- Medir relieve, pendientes y obstáculos a **escalas comparables** con la actividad (rover, perforación o EVA).
- Registrar temperatura de **aire, suelo y subsuelo** por separado, con hora, estación y profundidad.
- Documentar agua/hielo con tipo de evidencia, techo, espesor, contenido y variación espacial; documentar sales independientemente.
- Para polvo/erosión, distinguir deposición, transporte actual y formas fósiles.
- Añadir habitabilidad, preservación, detectabilidad y origen biológico como preguntas distintas.
- Añadir acceso, dueño o administrador, permisos, protección, temporada, seguridad de terreno y costos de campaña.
- Registrar qué no puede reproducir el campo terrestre: gravedad, presión/atmósfera y radiación marcianas. Estas variables requieren instalaciones o modelos complementarios.

### Fuentes principales y fecha de consulta

Consulta: **14/11/2026**. Las cifras corresponden al ámbito espacial y temporal indicado; no son valores universales.

**Jezero**

- **[J1]** NASA, [Mars 2020 science highlights](https://science.nasa.gov/mission/mars-2020-perseverance/science-highlights/).
- **[J2]** NASA, [elipse de aterrizaje de Perseverance](https://science.nasa.gov/resource/perseverance-rover-landing-ellipse-in-jezero-crater/).
- **[J3]** NASA, [ruta hacia el delta y unidades del piso](https://science.nasa.gov/resource/perseverances-route-to-the-delta-2/).
- **[J4]** Artículo de SuperCam, [Reflectance of Jezero Crater Floor: 2. Mineralogical Interpretation](https://doi.org/10.1029/2022JE007450), 2022/2023.
- **[J5]** Artículo de SuperCam, [Petrological Traverse of the Olivine Cumulate Séítah Formation](https://doi.org/10.1029/2022JE007638), 2023.
- **[J6]** Artículo SHERLOC, [Mineralogical Diversity in the Upper Fan Campaign](https://doi.org/10.1029/2024JE008750), 2025.
- **[J7]** Equipo Perseverance, [Lake- and groundwater-associated alteration of the olivine-rich Margin unit](https://pmc.ncbi.nlm.nih.gov/articles/PMC13593571/), 2026; las interpretaciones corresponden a afloramientos estudiados.
- **[J8]** Equipo MEDA, [One Martian Year of Near-Surface Temperatures at Jezero](https://doi.org/10.1029/2024JE008385), 2024; 700 soles.

**Gale**

- **[G1]** NASA, [A Guide to Gale Crater](https://science.nasa.gov/resource/a-guide-to-gale-crater/) y [Curiosity y Mount Sharp](https://science.nasa.gov/resource/nasas-curiosity-rover-explores-a-mountain-on-mars/).
- **[G2]** NASA, [Curiosity: misión y evidencia del lago de Yellowknife Bay](https://science.nasa.gov/wp-content/uploads/2024/03/CuriosityPoster.pdf) y [secuencia sedimentación/erosión](https://science.nasa.gov/resource/sedimentation-and-erosion-in-gale-crater-mars/).
- **[G3]** Estudio de Curiosity, [An Aeolian Depositional Sequence Shaped by Near-Surface Water at the Base of the Layered Sulfate Unit](https://doi.org/10.1029/2025JE009556), 2026.
- **[G4]** Estudio SAM-EGA, [Environmental Changes Recorded in Sedimentary Rocks in the Clay-Sulfate Transition Region](https://pubmed.ncbi.nlm.nih.gov/39619889/), 2024.

**Oxia y datos**

- **[O1]** ESA, [Rosalind Franklin rover mission](https://www.esa.int/missions/about-us/directorates/human-and-robotic-exploration/mars/exomars/rosalind-franklin-rover) y [detalles científicos e instrumento de perforación](https://explorationscience.esa.int/project/exomars-rosalind-franklin-rfm/).
- **[O2]** Fawdon et al. (2024), [The high-resolution map of Oxia Planum](https://doi.org/10.1080/17445647.2024.2302361), escala 1:30.000; [resumen de ESA](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/Best_geological_map_for_a_European_rover_on_Mars).
- **[O3]** [Ancient alluvial plains at Oxia Planum, Mars](https://www.sciencedirect.com/science/article/pii/S0012821X22005404), 2023; análisis orbital HiRISE/CTX/CaSSIS.
- **[M1]** NASA, [Mars Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/marsfact.html), contexto planetario; no cifras meteorológicas locales.
- **[M2]** NASA PDS, [archivo REMS de Curiosity](https://pdsatmospheres.nmsu.edu/data_and_services/atmospheres_data/MARS/curiosity/rems.html) y [ficha MEDA de Perseverance](https://pds.nasa.gov/ds-view/pds/viewContext.jsp?identifier=urn%3Anasa%3Apds%3Acontext%3Ainstrument%3Amars2020.meda&version=1.3). Registrar el conjunto de datos y las fechas de cada extracción.
- **[M3]** Equipo Mars Climate Database, [documentación](https://www-mars.lmd.jussieu.fr/mars/info_web/); salidas climáticas son simulaciones según escenario.
- **[D1]** NASA PDS, [Orbital Data Explorer](https://ode.rsl.wustl.edu/).
- **[D2]** ESA/Copernicus, [Explore Data](https://dataspace.copernicus.eu/explore-data/).
- **[D3]** JAXA, [G-Portal](https://gportal.jaxa.jp/).

---

## Caracterización de regiones de Marte para buscar análogos terrestres

**NASA Space Apps Challenge 2026 · Investigación Marte**  
**Fecha de corte:** 14 de noviembre de 2026  
**Base de trabajo:** texto consolidado del repositorio aportado por Matías, sus fuentes, artículos y datos previamente revisados de Arcadia–Amazonis/SWIM, y las fuentes primarias enlazadas al final.  
**Unidad de trabajo:** región y, cuando sea indispensable, unidad geológica o proceso dentro de ella. AP-1, AP-8 y AP-9 son observaciones locales que ayudan a interpretar Arcadia; no son el centro de este documento.

### 1. Propósito y método

Queremos describir **cómo son hoy** Arcadia–Amazonis, Jezero, Gale y Oxia Planum; **qué historia conservan**; **qué se quiere estudiar o ensayar allí**; y **cuáles de esas condiciones pueden buscarse o medirse en lugares terrestres**. Esta caracterización precede a elegir candidatos o construir un puntaje de similitud. El mismo terreno puede ser buen análogo de un proceso e inapropiado para otro.

Cada afirmación se clasifica como observación de rover o imagen, medición geofísica/espectral, interpretación, modelo o desconocido. El alcance espacial es crucial: un grano de muestra, una huella HiRISE, una unidad cartográfica y una región extensa no son intercambiables. También separamos ambiente marciano **actual** y procesos/ambientes **antiguos**.

| Región | Pregunta científica que mejor representa | Tipo de evidencia más fuerte | Condición terrestre que probablemente importe |
|---|---|---|---|
| Arcadia–Amazonis | ¿Cómo se distribuye y preserva el hielo bajo cobertura en llanuras de latitudes medias? | Impactos con hielo, relieve periglacial, neutrones, térmico y radar con interpretaciones en disputa | Suelo, permafrost/hielo enterrado, patrones criogénicos y medición independiente del subsuelo |
| Jezero | ¿Cómo interactuaron rocas ígneas, río, lago, delta y fluidos posteriores? ¿Dónde buscar señales conservadas? | Recorridos y análisis de Perseverance más cartografía orbital | Cuenca lacustre con delta, estratos y mineralogía contextualizada |
| Gale | ¿Cómo cambió y se alteró una sucesión de lago, arena eólica, agua subterránea y sales? | Estratigrafía, meteorología y geoquímica medidas por Curiosity | Secuencia sedimentaria con cambios verticales y alteración documentada |
| Oxia Planum | ¿Cómo se formaron y preservaron unidades antiguas con filosilicatos; qué se puede detectar bajo cobertura? | Cartografía y espectros orbitales; sin rover local todavía | Depósitos antiguos arcillosos con arquitectura fluvial y muestreo subsuperficial |

### 2. Condiciones de Marte comunes a las cuatro regiones

La atmósfera actual está dominada por CO₂ y tiene una presión de referencia cercana a **6,36 mbar (636 Pa) al radio medio**; cambia con altitud, latitud, estación y tiempo. La gravedad media es aproximadamente **3,73 m/s²**, ~38 % de la terrestre; un sol dura ~24 h 39 min. La ficha planetaria de NASA da temperatura media aproximada de **214 K (−59 °C)**. **Ninguna de estas cifras describe por sí sola una región o una hora local.** [P1]

Para un análogo de campo, radiación ionizante, presión y composición atmosférica, menor gravedad y radiación solar no quedan reproducidas simultáneamente. Pueden tratarse como límites de extrapolación o mediante ensayos instrumentales específicos. Incluso un lugar terrestre muy frío puede tener intercambio de calor, transporte eólico y ciclos de agua muy distintos.

| Dimensión común | Qué hay que distinguir | Por qué importa después |
|---|---|---|
| Aire y suelo | Temperatura del aire a altura definida, temperatura superficial y temperatura a profundidad | El hielo, el equipo y el operador responden a variables distintas |
| Polvo | Emisión, opacidad, deposición, abrasión y dinámica del transporte | Apariencia desértica no especifica efecto operativo |
| Agua | Hielo actual, sales hidratadas, agua líquida pasada y fluidos posteriores | Requieren instrumentos y análogos diferentes |
| Geología | Roca madre, cobertura, depósito, alteración y erosión | Composición parecida no demuestra mismo proceso |
| Biosignaturas | Habitabilidad, conservación, detección y origen biológico | Una señal prometedora puede tener explicación abiótica |
| Relieve | Pendiente a escala definida, rugosidad, obstáculos y estratigrafía | Llanura regional no implica circulación segura de un rover |

### 3. Arcadia–Amazonis: hielo enterrado y terreno de latitudes medias

#### 3.1 Extensión y paisaje

Nos interesa el límite entre Arcadia Planitia y Amazonis septentrional, con especial atención a llanuras próximas a **~40° N y ~200° E**. No hay una única «superficie de Arcadia»: se encuentran terrenos poligonales, mantos asociados a latitud, cráteres expandidos y algunas unidades sinuosas interpretadas como hielo enterrado bajo detritos. La transición hacia Amazonis incluye llanuras probablemente volcánicas bajo coberturas posteriores. Las unidades sinuosas y terrenos contiguos difieren en textura y respuesta térmica. [A1–A3]

Una cartografía de Ramsdale et al. examinó una franja de **300 km de ancho, 30–80° N**, centrada en **190° E**: describe variación de la región, no una medida de todos sus sectores. Un resumen de Hibbard et al. delimita tres unidades sinuosas aproximadamente entre **38–40° N y 194–204° E**. La geomorfología local estudiada por Luzzi et al. cubre huellas concretas dentro de este contexto. [A1–A3]

#### 3.2 Materiales, relieve y procesos

En las unidades sinuosas estudiadas se publicaron inercias térmicas de aproximadamente **200–250 J·m⁻²·K⁻¹·s⁻½**, frente a **100–200** en terrenos vecinos; son observaciones térmicas, no medidas directas de granulometría, resistencia ni porcentaje de hielo. Los autores interpretaron una cobertura superficial de partículas predominantemente arenosas y condiciones distintas en terrenos contiguos más finos. Otro estudio usó **196 J·m⁻²·K⁻¹·s⁻½** y albedo **0,23** como parámetros representativos de su modelo de Arcadia, no como constantes universales. [A2, A4]

A escala local, las huellas HiRISE de AP-1, AP-8 y AP-9 tienen desniveles máximos publicados de **31, 140 y 10 m**, respectivamente, sobre extensiones que **no son iguales**. En una subárea inmediata de 2,5 km² de AP-8 se informó 8 m. Los tamaños modales de polígonos de las tres huellas son **11,7, 12,1 y 10,7 m**. Son ejemplos de microrelieve para formular preguntas regionales; los desniveles no son pendientes y los tamaños no representan toda Arcadia. [A3]

Los patrones poligonales, cráteres expandidos, relieves invertidos y texturas semejantes a «brain terrain» son registros de contracción térmica, pérdida/modificación de hielo e impactos según distintas interpretaciones. Su presencia no indica que cada forma siga activa hoy, ni asegura que polígonos terrestres de aspecto similar tengan igual origen. Las unidades sinuosas tienen una hipótesis glacial respaldada por morfología, albedo, respuesta térmica y radar; el origen y contenido de cada capa aún requieren evaluación. [A2, A3]

#### 3.3 Hielo: evidencia y controversia

Hay evidencia **observacional** de hielo expuesto en algunos impactos de las latitudes medias, junto con señales orbitales compatibles con hielo en Arcadia. En la revisión local, una exposición aparece en un cráter a **~23 km** de AP-1, a **50–60 cm bajo la cota máxima del borde del cráter**: esa distancia no es la profundidad intacta de hielo bajo AP-1. El espaciado poligonal permite estimar **~8–12 cm** para cierta etapa de formación, no una medición actual en tres puntos. [A3]

Las interfaces de radar interpretadas por Bramson et al. dieron espesores regionales de **30–80 m** para un depósito, sometidos a supuestos dieléctricos. Campbell y Morgan reinterpretaron las pérdidas radar como incompatibles con que una gran fracción de todo el espesor esté dominada por hielo. Puede coexistir evidencia sólida de hielo somero en localidades con incertidumbre sobre continuidad, pureza y grosor de una unidad profunda. No se mezclan **profundidad del techo, espesor, fracción de hielo, porosidad y volumen extraíble**. [A4–A6]

SWIM integra geomorfología, neutrones, radar y térmico; el índice combinado de la tabla de Luzzi es **consistencia de evidencia**, no probabilidad ni porcentaje de hielo. La inspección del ZIP del equipo encontró capas auxiliares regionales de aproximadamente **3 km/píxel**, con GeoTIFF correspondientes de 0–1 m y 1–5 m idénticos y ponderaciones diferentes; no son dos mediciones independientes de profundidad. El enfoque probabilístico publicado por Courville et al. en 2026 es otro método y no transforma retroactivamente los índices de esa tabla en probabilidades. [A3, A7, A8]

#### 3.4 Clima, polvo, operaciones y biología

Se han observado remolinos de polvo y tormentas en Arcadia–Amazonis; no hay en lo recopilado una serie in situ de presión, viento y temperatura para una estación sobre la región estudiada. Una salida de la **Mars Climate Database** deberá llevar coordenadas, altitud, hora local, estación Ls y escenario de polvo, e identificarse como **modelo**. Dos imágenes orbitales o un parámetro térmico medio no reconstruyen el ciclo de temperatura diario o estacional. [A9, P2]

La evaluación histórica de zonas de aterrizaje consideró elevación, pendiente, rocas, reflectividad radar, soporte y proximidad al hielo; esos umbrales pertenecen a un concepto de misión, no son mediciones de toda la región ni garantías de suelo apto. No disponemos de cohesión, resistencia portante o excavabilidad cartografiadas con continuidad. Hielo y frío tampoco establecen una biosignatura o agua líquida actual. [A10]

**Preguntas de investigación/ensayo:** interpretar la relación entre cobertura, formas de terreno y hielo; probar detección no invasiva y perforación con control independiente; estudiar movilidad sobre polígonos/crestas y sesgos de mapas gruesos. Para buscar analogía terrestre interesan **terrenos de hielo enterrado cuya profundidad, tipo de hielo y suelo se hayan medido**, con microrelieve, acceso y permisos conocidos. Un valle árido sin hielo puede servir para polvo o navegación, pero no prueba la hipótesis criogénica.

### 4. Jezero: cráter, delta, piso ígneo y múltiples episodios de agua

#### 4.1 Forma y registro geológico

Jezero es una cuenca de impacto de unos **45 km** con red de entrada y abanico/delta occidental, piso y margen. Perseverance llegó en **febrero de 2021** y ha investigado unidades distintas; su recorrido no es una muestra aleatoria de todo el cráter. La geometría de estratos y clastos del delta respalda transporte fluvial y depósito en un antiguo lago. La secuencia y duración de fases lacustres, fluviales y posteriores se interpretan por unidad, no mediante un único rótulo «Jezero era un lago». [J1–J3]

Una sorpresa después del aterrizaje fue el carácter ígneo de partes del piso. Séítah contiene rocas ricas en cristales de olivino de escala milimétrica y piroxenos; también se examinaron unidades superiores diferentes. SuperCam registró minerales de alteración en baja proporción pero ampliamente distribuidos entre las rocas examinadas. La roca del piso, los sedimentos del abanico y los materiales marginales requieren perfiles de análogos distintos. [J4, J5]

En siete objetivos estudiados del abanico superior se reportaron carbonatos, sulfatos y fases compatibles con perclorato o fosfato, además de silicatos. Eso describe los objetivos, no una proporción de todas las sales del cráter. Un estudio de 2026 de la unidad marginal distingue afloramientos de olivino poco alterados de otros con carbonatos, sílice y vetas tardías, interpretando más de un episodio fluido; no convierte todos los márgenes en la misma costa sedimentaria. [J6, J7]

#### 4.2 Ambiente actual y astrobiología

**MEDA** mide meteorología en el trayecto. Un análisis publicado usa **700 soles** de temperatura de suelo y aire y muestra ciclos diarios/estacionales y variación de un sol a otro. Su coordenada cambiante, altura del sensor, hora y estación impiden asignar a todo Jezero un solo rango térmico o de presión sin un cálculo explícito. Hay viento y polvo; no se proporciona aquí un mapa regional de erosión, radiación o granulometría a escala de rueda. [J8]

Las arcillas y carbonatos en ciertos contextos, sedimentos finos y la interacción roca–agua motivan la búsqueda de señales de vida antigua. **Bright Angel** se ha descrito como una **biosignatura potencial**, no como confirmación biológica: es necesario descartar mecanismos no biológicos y conservar el contexto químico y estratigráfico. La habitabilidad pasada, la conservación de una señal y su detectabilidad son problemas distintos. No se ha establecido en esta investigación una reserva de hielo actual accesible comparable a la pregunta de Arcadia. [J9]

**Preguntas de investigación/ensayo:** cómo identificar en campo un delta y sus facies; distinguir materiales ígneos de sedimentarios y alteraciones posteriores; seleccionar muestras de un depósito con potencial de preservación; comparar texturas y mineralogía de carbonatos. En la Tierra hacen falta **cuencas o afloramientos con delta y estratigrafía comprobados**, muestras analizadas y controles de actividad biológica actual. Lago Salda es un antecedente conocido para algunas comparaciones carbonatadas, pero no es un análogo total ni necesariamente el candidato novedoso del proyecto. [J10]

### 5. Gale: historia sedimentaria, lagos, dunas y salmueras

#### 5.1 Relieve y sucesión

Gale es un cráter de unos **154 km** con la montaña sedimentaria Aeolis Mons/Mount Sharp. Curiosity aterrizó en **agosto de 2012** y estudia estratos de su base y ascenso. Los diferentes niveles dan acceso a cambios ambientales que se perdieron en otros lugares por erosión. La altura del edificio (del orden de 5 km) no representa pendientes transitables ni composición uniforme. [G1]

En Yellowknife Bay y otros estratos bajos hay lutitas y registros de agua dulce, ambientes lacustres y aportes de agua subterránea. Más arriba aparecen asociaciones con arcillas y sulfatos. En la transición no basta una narrativa sencilla de un lago que se secó para siempre: parte de la secuencia basal de la unidad de sulfatos incluye dunas y mantos eólicos, evidencia de humedecimiento, un intervalo lacustre y episodios de entrada fluvial. Un estudio de 2026 describe **~210 m de sección** en la transición con alternancia eólica/húmeda y concreciones enriquecidas en sulfatos de Ca y Mg; esa longitud corresponde a la sección investigada, no a todo Mount Sharp. [G2–G4]

SAM-EGA en muestras perforadas observa señales compatibles con ciertos filosilicatos, sulfatos, cloruros y otras fases según estrato; la diagénesis en fluidos salinos puede ocurrir después de depositado el sedimento. Es vital distinguir **ambiente de depósito** de **alteración posterior**. La presencia de compuestos orgánicos o de antiguos ambientes habitables no es detección de vida. [G5]

#### 5.2 Ambiente actual y uso como referencia

**REMS** proporciona observaciones in situ de temperatura del suelo/aire, presión y variables ambientales en el recorrido del rover. Hace falta escoger período y ubicación y revisar calibración y calidad antes de calcular una climatología de Gale. Comparar una capa que registra agua de hace miles de millones de años con el clima árido medido hoy como si fueran observaciones simultáneas produciría un análogo erróneo. Las laderas, dunas, afloramientos y piso tienen diferentes pendientes y obstáculos; no se atribuye una sola rugosidad al cráter. [G1, P3]

**Preguntas de investigación/ensayo:** reconstruir el paso entre lago, agua subterránea, sedimento eólico y diagénesis salina; testar cómo cambian y sobreviven señales químicas al enterrarse y erosionarse; practicar muestreo estratigráfico y travesía sobre roca y arena. Buscar en la Tierra **secuencias con contactos accesibles y documentados**, análisis mineralógicos de cada estrato y una historia de alteración independiente; un salar actual sin estratos lacustres/eólicos pertinentes reproduciría solo una parte.

### 6. Oxia Planum: llanuras antiguas arcillosas antes del rover

#### 6.1 Marco geográfico y evidencia

Oxia se sitúa cerca de **18° N** en el borde oriental de Chryse y cerca de la dicotomía de tierras altas y bajas. ESA la seleccionó para Rosalind Franklin; según la ficha de misión consultada, el lanzamiento está **programado para 2028**. A la fecha de corte **no existen observaciones de ese rover sobre la superficie de Oxia**. Su taladro está diseñado para llegar a **hasta 2 m**, lo que es capacidad instrumental proyectada y no una medición de hielo, orgánicos o suelo a esa profundidad. [O1]

Fawdon et al. (2024) publicaron un mapa a escala **1:30.000** que separa **15 unidades de roca en seis grupos y siete unidades texturales/superficiales**. Responde dónde podría muestrearse cada tipo de afloramiento y qué relaciones estratigráficas se espera comprobar. La clasificación orbital tiene incertidumbre de composición, espesores y transitabilidad que habrá de reevaluarse in situ. [O2]

Hay exposiciones extensas de **filosilicatos**, minerales compatibles con alteración en presencia de agua; se sitúan en materiales antiguos estimados alrededor de **3,9–4,0 mil millones de años** en el contexto del sitio de aterrizaje de ESA. El estudio de crestas sinuosas con HiRISE, CTX y CaSSIS interpreta depósitos de antiguos sistemas fluviales/aluviales en parte de la roca con arcillas. No asigna el mismo origen a cada afloramiento. Los materiales oscuros, sales, granulometría y estructura mecánica necesitan verificaciones específicas antes de imponer una composición regional uniforme. [O1–O3]

#### 6.2 Clima y objetivo de exploración

La temperatura del aire/suelo, presión, viento, opacidad, resistencia y radiación local no tienen serie de un rover sobre Oxia. Para caracterizar el ambiente presente pueden emplearse imágenes y productos orbitales según cobertura, y **modelos** con coordenadas, elevación, estación y escenario explícitos. Hasta hacer ese procesamiento no corresponde adjudicar a Oxia un rango meteorológico local de otra misión. [P2]

Rosalind Franklin busca señales morfológicas y químicas potencialmente conservadas en materiales antiguos; taladrar bajo la superficie puede reducir exposición de las muestras, pero **la arcilla no garantiza preservación ni vida**. Hay que distinguir historia de habitabilidad, conservación de compuestos, posibilidad real de medirlos y prueba de origen biológico. [O1]

**Preguntas de investigación/ensayo:** distinguir unidades arcillosas y superficies que las ocultan; reconstruir un antiguo sistema aluvial por estratigrafía y mineralogía; diseñar selección de muestras y perforación que controle contaminación y alteración. Un candidato terrestre útil requiere **afloramientos antiguos con arcillas identificadas, geometría fluvial contrastada y profundidad/condición del material medibles**. Su actividad biológica y erosión posteriores son limitaciones a documentar.

### 7. De la caracterización marciana a criterios de comparación, sin elegir aún lugares

La tabla traduce cada **objetivo de investigación** en propiedades observables. Es un borrador de requisitos para la siguiente fase; no asigna pesos ni declara equivalencias. Los campos absolutos dependen del instrumento y del polígono finalmente seleccionado.

| Objetivo y referencia | Propiedades marcianas que definen la tarea | Variables que habrá que medir en Tierra | Necesidad de validación |
|---|---|---|---|
| Hielo cubierto, Arcadia | Cobertura, hielo somero, morfología criogénica, heterogeneidad | Profundidad del techo, espesor, fracción de hielo, composición y textura de cobertura, geometría poligonal | Perforación/medición geofísica + control de campo; no solo imagen |
| Navegación en llanura criogénica, Arcadia | Polígonos, crestas, cráteres y terrenos vecinos de distinta respuesta térmica | Pendiente por distancia de base, rugosidad, obstáculos, suelo portante | Escala acorde a vehículo y repetición de recorridos |
| Depósito deltaico, Jezero | Relación río–delta–cuenca y facies | Estratigrafía, granulometría, mineralogía y geometría del delta | Campo + imágenes + secciones de sedimento |
| Alteración ígnea, Jezero | Piso rico en olivino/piroxeno, cambios por fluidos, margen | Roca madre, fases secundarias, cronología relativa y agua/roca | Petrografía y análisis químico, no solo color |
| Transición de ambientes, Gale | Lago, mantos eólicos, entradas de agua y diagénesis salina | Contactos, facies, sales por estrato, textura y edad relativa | Muestreo a lo largo de sección y controles de alteración |
| Arcillas y muestreo, Oxia | Material antiguo con filosilicatos, crestas fluviales, cobertura | Identidad mineral, roca hospedante, facies, espesor de cobertura y profundidad de muestreo | Espectros + muestreo y test de perforación |
| Señales potenciales, Jezero/Gale/Oxia | Habitabilidad, preservación, detectabilidad y alternativas abióticas | Matriz, orgánicos/minerales, profundidad, biología actual y controles | Protocolo contra contaminación y falsos positivos |
| Polvo y ambiente operativo, varias | Polvo suspendido/depositado, temperatura y transporte | Tamaño y mineralogía de partículas, flujo, deposición, temperatura aire/suelo | Especificar tarea; corregir por atmósfera/gravedad |

**Comparabilidad:** la unidad candidata en la Tierra se representará mediante un polígono y muestras; se guardará la región/proceso marciano correspondiente, fecha, método, resolución y nivel de confianza. No se exige que una sola región terrestre reproduzca todas las filas.

### 8. Qué se ha medido, qué se puede obtener y qué aún no sabemos

| Atributo | Arcadia–Amazonis | Jezero | Gale | Oxia |
|---|---|---|---|---|
| Topografía/geomorfología | Orbital, más huellas locales de alta resolución | Orbital y recorrido | Orbital y recorrido | Orbital y mapa 1:30.000 |
| Mineralogía | Inferencias regionales; cobertura local incompleta | Instrumentos de superficie + orbital, por unidad | Muestreo de superficie por estrato + orbital | Espectros orbitales; validación local pendiente |
| Historia de agua | Hielo pasado/presente interpretado y observado en localidades | Agua antigua y alteración documentada | Ambientes antiguos múltiples y alteración documentados | Alteración/fluvial antigua inferida |
| Hielo actual | Evidencias diversas; espesor/composición profunda discutidos | Sin recurso equivalente establecido aquí | Sin recurso equivalente establecido aquí | Sin recurso equivalente establecido aquí |
| Temperatura y presión **locales** | Sin estación meteorológica de la zona revisada | MEDA, si se procesa serie elegida | REMS, si se procesa serie elegida | Sin estación in situ; orbital/modelado |
| Mecánica continua del suelo | No medida aquí | Medidas y observaciones en recorrido, no cráter entero | Medidas y observaciones en recorrido, no cráter entero | No medida in situ |
| Evidencia biológica confirmada | Ninguna | Ninguna | Ninguna | Ninguna; rover pendiente |

Este cuadro distingue **«no procesado», «no medido» y «sin evidencia confirmada»**. Los valores de otros puntos no rellenan las lagunas. Hay trabajo adicional si la siguiente fase exige comparar temperaturas, pendientes o composición con umbrales: definir polígono, recuperar producto, filtrar datos y cuantificar incertidumbre.

### 9. Repositorios: qué usar para Marte y qué usar para la Tierra

| Fuente | Función concreta en este proyecto | Precaución |
|---|---|---|
| NASA PDS / Orbital Data Explorer | Buscar CTX/HiRISE (morfología), CRISM (espectros), SHARAD (subsuelo), MCS (atmósfera) y otras colecciones por región | Verificar huella, período, resolución y calidad [D1] |
| NASA PDS, MEDA y REMS | Series in situ en recorridos de Jezero y Gale | Control de calidad, altura, posición y hora; no extrapolar a toda la región [P3] |
| ESA Planetary Science Archive, Mars Express HRSC/OMEGA y TGO CaSSIS | Contexto topográfico/espectral y estructuras orbitales; CaSSIS usado en el estudio de Oxia | Confrontar resolución y cobertura con NASA [O3] |
| SWIM y documentación de métodos | Síntesis de evidencias de hielo en latitudes medias | Diferenciar índice, probabilidad, área y profundidad [A7, A8] |
| NASA Earthdata / Worldview | Descubrir y visualizar observaciones de candidatos **terrestres** | Producto visual no demuestra contenido de hielo subsuperficial [D2] |
| ESA Copernicus Data Space | Sentinel para cobertura, cambios y propiedades terrestres | SAR y óptico miden cosas distintas; verificar licencia y producto [D3] |
| JAXA G-Portal | Observación terrestre según sensor/variable disponible | No atribuir a Marte variables de satélites terrestres [D4] |
| CSA RADARSAT-1 / RCM | Radar de candidatos terrestres cuando haya producto pertinente | Retrodispersión no es medida directa de profundidad de hielo [D5] |
| LRO/Diviner | Comparador lunar del trabajo paralelo | No aporta temperaturas de Marte |

La investigación de gabinete de este documento **reúne publicaciones y datos ya inspeccionados en el repositorio**. No hemos ejecutado aquí nuevas extracciones regionales de MCD, REMS, MEDA, CRISM o imágenes Sentinel. Un catálogo honesto tendrá un campo «dato pendiente» cuando la variable aún no se haya procesado.

### 10. Decisión metodológica para la siguiente fase

Primero definiremos una **actividad análoga específica** para cada búsqueda; luego afinaremos qué variables y mínimos son indispensables, cuáles son deseables y cuáles solo aportan contexto. Por ejemplo, hielo demostrado a profundidad medible es indispensable para ensayar un detector de hielo, pero no para entrenar a un geólogo a distinguir facies deltaicas. Las ponderaciones, el ranking de lugares y los filtros del futuro catálogo vendrán después de verificar los datos terrestres.

Para cada candidato terrestre se necesitará: localización y límites; evidencia geológica y ambiental primaria; estación temporal; muestras y/o validación de campo; acceso legal, permisos, conservación y costos; comparación con al menos un análogo conocido; y lista expresa de diferencias respecto a la tarea marciana. La originalidad será útil si ese sitio cubre un vacío concreto de investigación o acceso y está respaldado por datos suficientes.

### Referencias principales

**Material del equipo.** secciones anteriores de `matydrox.md`, que incluye la investigación inicial de Marte, la revisión regional Arcadia–Amazonis y SWIM, la ficha AP-1 y la comparación Jezero/Gale/Oxia. Referencias internas de AP y SWIM proceden de allí. Los apartados anteriores no convierten automáticamente análisis propuestos en resultados ejecutados.

**Contexto, hielo y Arcadia:**

- **[P1]** NASA NSSDC, [Mars Fact Sheet](https://nssdc.gsfc.nasa.gov/planetary/factsheet/marsfact.html). Variables medias planetarias, no regionales.
- **[P2]** Mars Climate Database, [documentación del acceso](https://www-mars.lmd.jussieu.fr/mars/info_web/). Simulaciones con escenarios de polvo; no se calcularon aquí valores locales.
- **[P3]** NASA PDS Atmospheres, [archivo REMS](https://pdsatmospheres.nmsu.edu/data_and_services/atmospheres_data/MARS/curiosity/rems.html); NASA PDS, [contexto MEDA](https://pds.nasa.gov/ds-view/pds/viewContext.jsp?identifier=urn%3Anasa%3Apds%3Acontext%3Ainstrument%3Amars2020.meda&version=1.3).
- **[A1]** Ramsdale et al. (2019), [*Grid Mapping the Northern Plains of Mars: ... Arcadia Planitia*](https://doi.org/10.1029/2018JE005663).
- **[A2]** Hibbard et al. (2018), [*Evidence for Flow in Buried Ice in the Mid-Latitudes of Arcadia Planitia*](https://www.hou.usra.edu/meetings/lpsc2018/pdf/2606.pdf), resumen de congreso; Hibbard et al. (2021), [*Evidence for widespread glaciation in Arcadia Planitia*](https://doi.org/10.1016/j.icarus.2020.114298).
- **[A3]** Luzzi et al. (2025), [*Geomorphological Evidence of Near-Surface Ice at Candidate Landing Sites in Northern Amazonis Planitia*](https://doi.org/10.1029/2024JE008724). PDF aportado en la investigación previa; tablas 2–3 y métodos.
- **[A4]** Bramson et al. (2017), [*Preservation of Midlatitude Ice Sheets on Mars*](https://doi.org/10.1002/2017JE005357); basado entre otros en Bramson et al. (2015), [*Widespread excess ice in Arcadia Planitia*](https://doi.org/10.1002/2015GL064844).
- **[A5]** Campbell y Morgan (2018), [*Fine-Scale Layering ... From Multiband SHARAD Data Processing*](https://doi.org/10.1002/2017GL075844), interpretación alternativa de pérdidas radar.
- **[A6]** Piqueux et al. (2019), [*Widespread Shallow Water Ice on Mars at High Latitudes and Midlatitudes*](https://doi.org/10.1029/2019GL083947), modelo térmico y heterogeneidad.
- **[A7]** Morgan, Putzig et al. (2025), [*Refined Mapping of Subsurface Water Ice on Mars to Support Future Missions*](https://doi.org/10.3847/PSJ/ad9b24); ZIP SWIM aportado e inspeccionado previamente.
- **[A8]** Courville et al. (2026), [*Subsurface Water Ice Mapping on Mars: A Probabilistic Approach*](https://pubs.usgs.gov/publication/70279509), nuevo método; no se calcularon sus productos en este documento.
- **[A9]** Heavens (2017), [tormentas de polvo en Amazonis–Arcadia](https://doi.org/10.1175/JAS-D-16-0211.1); Stanzel et al. (2006), [remolinos activos observados por HRSC](https://doi.org/10.1029/2006GL025816).
- **[A10]** Golombek et al. (2021), [*SpaceX Starship Landing Sites on Mars*](https://www.hou.usra.edu/meetings/lpsc2021/pdf/2420.pdf), evaluación histórica y criterios de una misión.

**Jezero:**

- **[J1]** NASA, [Perseverance science highlights](https://science.nasa.gov/mission/mars-2020-perseverance/science-highlights/).
- **[J2]** Mangold et al. (2021), [*Perseverance rover reveals an ancient delta-lake system and flood deposits at Jezero crater*](https://doi.org/10.1126/science.abl4051).
- **[J3]** NASA, [ruta del piso al delta](https://science.nasa.gov/resource/perseverances-route-to-the-delta-2/).
- **[J4]** Estudio SuperCam, [mineralogía del piso](https://doi.org/10.1029/2022JE007450).
- **[J5]** Estudio SuperCam, [roca ígnea de Séítah](https://doi.org/10.1029/2022JE007638).
- **[J6]** Estudio SHERLOC, [mineralogía del abanico superior](https://doi.org/10.1029/2024JE008750).
- **[J7]** Estudio 2026, [alteración de la unidad marginal](https://pmc.ncbi.nlm.nih.gov/articles/PMC13593571/).
- **[J8]** Estudio MEDA (2024), [un año marciano de temperaturas](https://doi.org/10.1029/2024JE008385).
- **[J9]** Artículo 2025, [*Redox-driven mineral and organic associations in Jezero Crater*](https://doi.org/10.1038/s41586-025-09413-0); «potencial» no es veredicto biológico.
- **[J10]** NASA Earth Observatory, [Lake Salda como antecedente de analogía parcial](https://science.nasa.gov/earth/earth-observatory/jez-like-mars-147041/).

**Gale:**

- **[G1]** NASA, [*A Guide to Gale Crater*](https://science.nasa.gov/resource/a-guide-to-gale-crater/) y [Curiosity y Mount Sharp](https://science.nasa.gov/resource/nasas-curiosity-rover-explores-a-mountain-on-mars/).
- **[G2]** NASA, [primeros resultados de Curiosity/Yellowknife Bay](https://science.nasa.gov/wp-content/uploads/2024/03/CuriosityPoster.pdf).
- **[G3]** Estudio de Curiosity (2026), [secuencia eólica y agua en base de unidad con sulfatos](https://doi.org/10.1029/2025JE009556).
- **[G4]** Estudio de Curiosity (2026), [evaporitas y transición arcilla–sulfato](https://doi.org/10.1029/2026JE009783).
- **[G5]** Estudio SAM-EGA (2024), [alteración y sales en la transición arcilla–sulfato](https://pubmed.ncbi.nlm.nih.gov/39619889/).

**Oxia y portales:**

- **[O1]** ESA, [ficha actual de Rosalind Franklin](https://www.esa.int/missions/about-us/directorates/human-and-robotic-exploration/mars/exomars/rosalind-franklin-rover) y [ciencia e instrumentos](https://explorationscience.esa.int/project/exomars-rosalind-franklin-rfm/).
- **[O2]** Fawdon et al. (2024), [*The high-resolution map of Oxia Planum*](https://doi.org/10.1080/17445647.2024.2302361).
- **[O3]** [*Ancient alluvial plains at Oxia Planum*](https://www.sciencedirect.com/science/article/pii/S0012821X22005404), 2023; HiRISE/CTX/CaSSIS.
- **[D1]** NASA PDS, [Orbital Data Explorer](https://ode.rsl.wustl.edu/) y [datos MRO](https://pds-geosciences.wustl.edu/missions/mro/default.htm).
- **[D2]** NASA, [Earthdata](https://search.earthdata.nasa.gov/) y [Worldview](https://worldview.earthdata.nasa.gov/).
- **[D3]** ESA, [Copernicus Data Space](https://dataspace.copernicus.eu/explore-data/).
- **[D4]** JAXA, [G-Portal](https://gportal.jaxa.jp/).
- **[D5]** CSA, [RADARSAT-1](https://donnees-data.asc-csa.gc.ca/en/dataset/radarsat1) y [RCM](https://donnees-data.asc-csa.gc.ca/en/dataset/rcm).

---

## Paso 1 — Preguntas de exploración marciana que guiarán la búsqueda de análogos terrestres

**NASA Space Apps Challenge 2026 · Línea Marte**  
**Fecha:** 14 de noviembre de 2026  
**Insumos:** investigación de Marte consolidada en el texto del repositorio aportado por Matías y [caracterización regional de Arcadia–Amazonis, Jezero, Gale y Oxia](#caracterización-de-regiones-de-marte-para-buscar-análogos-terrestres).  
**Alcance:** definir preguntas y condiciones de comparación. Los lugares terrestres se identificarán y caracterizarán en el paso siguiente.

### 1. Qué resultado debe producir esta etapa

El desafío exige **encontrar y caracterizar una o más ubicaciones en la Tierra** que sirvan para preparar exploración lunar o marciana, utilizando datos abiertos y explicando utilidad y límites. Esta línea del equipo prepara la búsqueda de análogos **marcianos**. La caracterización de Marte nos dice *qué buscar*; el producto final tendrá que mostrar *dónde está en la Tierra* y qué pruebas respaldan la comparación.

Por ello, cada pregunta de la tabla siguiente debe desembocar en una decisión verificable sobre un lugar terrestre. No se buscará un «Marte terrestre» genérico ni se asignará a una región marciana una única composición, temperatura o geología. Distinguiremos condiciones **actuales** de operaciones y procesos **antiguos** registrados en rocas.

#### Estructura de cada pregunta

1. **Qué queremos aprender o ensayar** para una misión.
2. **Qué proceso o material marciano** es la referencia y en qué unidad de la región ocurre.
3. **Qué propiedad observable** debe tener el candidato terrestre.
4. **Cómo se demostraría** con imagen, dato geofísico, mapa, muestra o medición de campo.
5. **Qué diferencia Tierra–Marte limita** las conclusiones.

Un proceso puede ser comparable aunque temperatura y presión sean diferentes. Para algunos ensayos la presencia física de hielo es indispensable; para otros solo importa la geometría de un terreno y la logística de recorrerlo.

### 2. Preguntas derivadas de Arcadia–Amazonis

#### A1. Detección de hielo enterrado bajo una cobertura variable

**Pregunta de misión:** ¿cómo detectar y delimitar hielo subsuperficial, distinguirlo de roca o suelo seco y estimar a qué profundidad empieza antes de perforar?

**Por qué Arcadia:** existen exposiciones de hielo en localidades observadas, señales orbitales y morfologías compatibles con hielo, pero la continuidad, composición y profundidad varían o permanecen discutidas. Las interpretaciones de depósitos de decenas de metros por radar no equivalen a una medida del techo de hielo en cada sitio. Los polígonos son pistas, no perforaciones. [R1]

| Papel del atributo | Qué debería ofrecer un sector terrestre | Verificación necesaria |
|---|---|---|
| **Esencial para este ensayo** | Material helado enterrado y cobertura superficial accesible | Perforación, exposición natural documentada o sondeo geofísico contrastado por campo |
| **Esencial** | Espesor de cobertura y profundidad del techo del hielo en puntos georreferenciados | Perfiles o muestras; incertidumbre y variación lateral |
| **Esencial** | Materiales con y sin hielo dentro de un área de ensayo | Controles negativos, para probar si el método genera falsos positivos |
| **Valioso** | Polígonos, hundimientos o relieves criogénicos bien cartografiados | Geometría, origen y edad relativa comprobados |
| **Valioso** | Granulometría, humedad, sales y propiedades dieléctricas de la cobertura | Muestreo y laboratorio en vez de inferencia visual |

**Escalas a comparar:** decímetros a metros en perfiles verticales, metros a kilómetros para continuidad espacial. No fijamos «hielo a 10 cm» como requisito: en los estudios marcianos ese número depende de una interpretación de formación del terreno. **Límite terrestre:** agua líquida estacional, atmósfera densa y distinto régimen térmico pueden cambiar el mecanismo de formación y la respuesta instrumental.

**Resultado que ofrecería el candidato:** un sitio donde ocultar a los operadores las posiciones conocidas del hielo, ejecutar radar u otros métodos y contrastar las predicciones con sondeos reales. Es una idea de ensayo futuro, no un experimento que este documento ya haya realizado.

#### A2. Movilidad y operaciones sobre terreno poligonal

**Pregunta de misión:** ¿cómo planear recorridos y seleccionar áreas de trabajo cuando una llanura a escala orbital contiene crestas, surcos, bloques y suelos de resistencia variable?

Aquí **el hielo no tiene que estar presente** si la tarea es exclusivamente cartografía y navegación sobre obstáculos; sí importa si se ensaya hundimiento o tracción en suelo helado. El candidato debe disponer de un polígono delimitado, modelo de elevación apropiado, inventario de obstáculos, pendiente calculada a longitudes de base especificadas y, para pruebas mecánicas, resistencia/compactación medidas. Los polígonos de las huellas HiRISE estudiadas en la transición Arcadia–Amazonis presentan tamaños modales del orden de 11–12 m; no constituyen un valor universal de Arcadia. [R1]

**Comprobación decisiva:** un terreno parece liso en un píxel de decenas de metros, pero el recorrido de un rover encuentra obstáculos menores. Comparar mapas de distintas resoluciones y realizar un trayecto de prueba permite cuantificar esa pérdida de información. El entorno terrestre no reproduce por sí solo gravedad ni presión de Marte.

#### A3. Interpretar formación y degradación del terreno con hielo

**Pregunta científica:** ¿qué combinación de contracción térmica, sublimación, cubierta de sedimentos, impactos y posible flujo de hielo puede generar formas observadas en Arcadia?

Se necesitan en la Tierra **formas y procesos documentados**, no únicamente polígonos parecidos. Un sitio fuerte tendrá historial de temperatura del suelo, mediciones de hielo y sedimento, cartografía multitemporal y estudios que expliquen el mecanismo. Si las formas son relictas, debe distinguirse el ambiente en que se formaron del clima actual. El candidato puede representar un mecanismo específico aunque no toda la historia de Arcadia.

### 3. Preguntas derivadas de Jezero

#### J1. Reconocer y muestrear un sistema río–delta–lago

**Pregunta de misión:** ¿cómo identificar en imágenes y en terreno las facies de un antiguo delta, reconstruir la dirección del transporte y escoger muestras con contexto estratigráfico?

Jezero contiene un delta occidental y evidencias de actividad fluvial/lacustre. El candidato terrestre debe tener una conexión geométrica verificable entre cuenca, entrada, depósitos y estratos, más sedimentos accesibles para validar lo que se interpretó desde imágenes. Se necesita cartografía de facies y tamaños de grano, no solo la vista aérea de una forma triangular. Una cuenca actual puede ayudar a entender deposición; otra antigua y expuesta puede servir mejor para ensayar preservación y muestreo. [R2]

**Escalas:** cuenca y abanico en kilómetros, afloramientos en metros, láminas y granos en centímetros a micras. **Límite terrestre:** las tasas de agua, erosión, vegetación y actividad microbiana pueden ser muy diferentes.

#### J2. Diferenciar roca ígnea, sedimento y alteración por fluidos

**Pregunta de misión:** si un piso parece lacustre desde órbita, ¿cómo distinguir roca ígnea de sedimento y reconocer alteración acuosa posterior?

Perseverance encontró rocas ígneas ricas en olivino y piroxenos en partes del piso; también hay minerales secundarios y materiales diferentes en el abanico y margen. [R2] Un análogo requiere afloramientos donde **roca original, contactos y minerales secundarios** estén medidos por petrografía/espectros/análisis químico. Son especialmente útiles exposiciones donde una clasificación hecha solo con imágenes pueda ponerse a prueba con muestras. Coincidencia de color o reflectancia, sin contexto, no demuestra el mismo origen.

#### J3. Seleccionar muestras con posibilidad de conservar señales antiguas

**Pregunta de misión:** ¿qué estratos y minerales ofrecen mejores condiciones de preservación y cómo evitar confundir una señal geológica o química con una biológica?

Pueden compararse depósitos finos, carbonatos y materiales alterados con documentación de enterramiento, erosión y biología posterior. Deben incluirse controles abióticos y contaminación. La asociación mineral/orgánica descrita en Bright Angel es una **biosignatura potencial**, no vida confirmada. [R2] Un candidato no necesita tener vida ausente: debe permitir saber qué señales produjo la vida terrestre y cuáles pueden generarse sin ella.

### 4. Preguntas derivadas de Gale

#### G1. Reconstruir cambios de ambiente a partir de una secuencia

**Pregunta de misión:** ¿cómo reconocer en un recorrido geológico cuándo un depósito registra lago, aportes fluviales, dunas o mantos de arena eólica?

Gale proporciona estratos con facies lacustres y eólicas; estudios recientes muestran episodios húmedos dentro de tramos dominados por procesos eólicos. [R3] Un análogo debe ofrecer **contactos de unidades accesibles** y una sección descrita capa por capa: estructuras sedimentarias, composición, granulometría y relaciones de superposición. No basta juntar en un mismo mapa un lago y una duna separados sin una relación estratigráfica demostrable.

#### G2. Separar sales depositadas originalmente de alteración posterior

**Pregunta científica:** ¿las arcillas, sulfatos y cloruros registran el ambiente de depósito o fluidos que circularon después?

Para ensayar la interpretación se buscan secciones con arcillas y sales **identificadas por estrato**, vetas o concreciones, análisis de roca hospedante y evidencia temporal relativa de diagénesis. Curiosity ha observado cambios mineralógicos y señales de fluidos salinos posteriores en la transición arcilla–sulfato. [R3] Un salar moderno puede representar formación de ciertas sales, pero por sí solo no reproduce esta sucesión estratigráfica.

#### G3. Planear un recorrido y seleccionar perforaciones en estratos heterogéneos

**Pregunta operativa:** ¿qué muestras aportan la mayor información al recorrer capas de distinta dureza, pendiente y accesibilidad?

El candidato terrestre necesitará afloramientos conectados, rutas posibles, afloramientos de referencia y permisos para muestreo o perforación. El rendimiento se evaluaría por si las decisiones de ruta y muestreo capturan la transición geológica conocida, no por parecido fotográfico de una montaña. Temperatura y presión son límites físicos a controlar aparte.

### 5. Preguntas derivadas de Oxia Planum

#### O1. Identificar arcillas y entender su roca hospedante

**Pregunta de misión:** ¿qué partes de una llanura con señal orbital de filosilicatos son afloramientos accesibles y qué proceso produjo las arcillas?

Oxia posee extensas exposiciones cartografiadas de minerales arcillosos, pero el mapa orbital aún no se ha validado allí mediante un rover. [R4] Un candidato terrestre tendrá mapa espectral, **especies de arcilla identificadas con muestras** y descripción de la roca hospedante; debe permitir contrastar predicciones remotas con observación de campo. La presencia de arcilla no demuestra por sí sola un ambiente habitable.

#### O2. Reconstruir antiguos depósitos aluviales mediante relieve y estratigrafía

**Pregunta científica:** ¿cómo distinguir crestas sinuosas de origen fluvial y relacionarlas con unidades portadoras de arcillas?

Una forma sinuosa aislada no basta. El candidato debe reunir geometría de canales o depósitos, perfiles topográficos, estructura sedimentaria y mineralogía que sustenten la interpretación. En Oxia se han interpretado crestas como restos de antiguos sistemas aluviales; no es un origen asignable por igual a todas sus unidades. [R4]

#### O3. Ensayar selección de muestras bajo cobertura

**Pregunta de misión:** ¿puede una campaña que combina mapas, observación de superficie y perforación encontrar materiales menos alterados o contaminados bajo la cubierta?

Hacen falta variaciones conocidas de espesor y composición de cubierta, testigos o exposiciones a profundidades medidas, y controles de contaminación. Los **hasta 2 m** del taladro de Rosalind Franklin son una capacidad planificada, no una profundidad marciana universal a igualar. [R4] La analogía debe evaluar rendimiento de un método de búsqueda y muestreo, no suponer que la profundidad garantice la preservación.

### 6. Preguntas que cruzan varias regiones

| Pregunta transversal | Regiones donde aporta | Evidencia terrestre que necesitaríamos | Cuándo importa |
|---|---|---|---|
| ¿Cómo cambia el terreno visto por satélite al comprobarlo en campo? | Las cuatro | Imagen georreferenciada, elevación, muestras y puntos de validación | Siempre que el descubrimiento dependa de datos orbitales |
| ¿Cómo separar agua antigua, hielo presente y sales? | Arcadia, Jezero, Gale, Oxia | Datación relativa, mineralogía y medidas actuales del subsuelo | Cuando se invocan «recursos» o «habitabilidad» |
| ¿Cómo afectan polvo y arena a observaciones y operaciones? | Las cuatro | Granulometría, aerosol/deposición, viento y desempeño de equipos | En ensayos de sensores, movilidad o energía |
| ¿Dónde se rompe una inferencia de biofirma? | Jezero, Gale, Oxia | Controles bióticos/abióticos y contaminación | En muestreo astrobiológico |
| ¿Qué puede extrapolarse bajo baja presión/gravedad? | Las cuatro | Comparación dimensional o ensayos controlados adicionales | Si se extrapola mecánica, erosión o fluidos |

Las condiciones planetarias no serán «casillas obligatorias» de un sitio de campo terrestre. Aire, radiación y gravedad se registran como diferencias que pueden exigir experimentos complementarios.

### 7. Orden para iniciar la búsqueda terrestre

Estas son **prioridades prácticas para iniciar**, no un ranking científico de regiones ni la elección definitiva de una misión:

| Orden | Línea | Por qué resulta comprobable | Condición de descarte inicial |
|---|---|---|---|
| 1 | **A1 — hielo enterrado en Arcadia** | Se puede contrastar detección remota con perforaciones o exposiciones y controles secos | Sin hielo verificado o sin profundidad conocida, no vale para ensayar detección de hielo |
| 2 | **O1/O2 — arcillas y depósitos aluviales de Oxia** | Permite medir si imágenes/espectros predicen mineralogía y facies reales | Solo color/forma, sin muestras mineralógicas ni contexto |
| 3 | **J1/J2 — delta e ígneo alterado de Jezero** | Hay dos preguntas distintas que pueden aportar candidatos inesperados | Mezclar afloramientos inconexos como si fueran una secuencia |
| 4 | **G1/G2 — sucesión y sales de Gale** | Muy informativo si existe una sección larga, accesible y estudiada | Sales sin relación estratigráfica ni análisis de alteración |

Este orden ayuda a repartir trabajo y delimitar consultas. Un candidato terrestre inesperado puede surgir de cualquier línea. Los análogos conocidos —por ejemplo Atacama, Qaidam, Haughton o Lanzarote— se usarán como **comparadores por tarea**; la propuesta debe caracterizar al menos un sector terrestre concreto y mostrar qué aportaría frente a ellos.

### 8. Plantilla para pasar de una pregunta a un candidato terrestre

| Campo obligatorio | Ejemplo de contenido, todavía sin elegir un lugar |
|---|---|
| ID de pregunta | A1, J1, G2 u O1 |
| Tarea | Detectar hielo, interpretar un delta, distinguir diagénesis, etc. |
| Unidad marciana | Subunidad/ambiente dentro de la región y límites de la fuente |
| Polígono terrestre | Coordenadas y superficie del sector específico |
| Propiedad indispensable | Qué presencia/proceso debe comprobarse |
| Variable y unidad | Profundidad (m), tamaño de grano (µm/mm), pendiente (° sobre base definida), especie mineral, etc. |
| Método y fuente | Producto satelital, mapa, artículo, sondeo y fecha |
| Escala y confianza | Tamaño de píxel, número de muestras, incertidumbre e interpretación |
| Diferencias importantes | Presión, gravedad, biología, clima, agua líquida |
| Utilidad | Qué instrumento, hipótesis o procedimiento podría ponerse a prueba |
| Uso real | Acceso, permisos, protección, temporada y posibilidad de muestrear |
| Estado | Hipótesis / candidato prometedor / caracterizado con mediciones |

**Regla de decisión:** una imagen sugiere una ubicación; evidencia independiente decide si pasa a candidato. «Nuevo» se referirá a un lugar o proceso poco utilizado como análogo *para esa tarea*, no a la ausencia total de estudios: hacen falta datos suficientes para defenderlo.

### 9. Resultado y siguiente paso

Ya están definidas **doce preguntas específicas** (A1–A3, J1–J3, G1–G3, O1–O3), sus condiciones y el tipo de validación. El siguiente paso es buscar sectores terrestres mediante NASA Earthdata, Copernicus, JAXA, cartografía geológica y literatura de campo. Allí construiremos una lista corta con coordenadas y pruebas de los atributos indispensables. La comparación final deberá decir qué aprende una misión del lugar propuesto y qué aspectos marcianos no reproduce.

### Fuentes de esta derivación

- **[R1] Arcadia–Amazonis.** [Caracterización regional consolidada](#caracterización-de-regiones-de-marte-para-buscar-análogos-terrestres), secciones 3 y 7; Luzzi et al. (2025), [geomorfología de sitios próximos](https://doi.org/10.1029/2024JE008724); Bramson et al. (2017), [preservación de hielo](https://doi.org/10.1002/2017JE005357); Campbell y Morgan (2018), [alternativa de interpretación radar](https://doi.org/10.1002/2017GL075844).
- **[R2] Jezero.** Documento regional, sección 4; Mangold et al. (2021), [delta y depósitos de inundación](https://doi.org/10.1126/science.abl4051); [mineralogía del piso](https://doi.org/10.1029/2022JE007450); [artículo de Bright Angel](https://doi.org/10.1038/s41586-025-09413-0).
- **[R3] Gale.** Documento regional, sección 5; [secuencia eólica y agua en la base de la unidad con sulfatos](https://doi.org/10.1029/2025JE009556); [evaporitas en la transición arcilla–sulfato](https://doi.org/10.1029/2026JE009783); [análisis SAM-EGA](https://pubmed.ncbi.nlm.nih.gov/39619889/).
- **[R4] Oxia.** Documento regional, sección 6; Fawdon et al. (2024), [mapa geológico a 1:30.000](https://doi.org/10.1080/17445647.2024.2302361); [sistemas aluviales antiguos](https://www.sciencedirect.com/science/article/pii/S0012821X22005404); [ESA, misión Rosalind Franklin](https://explorationscience.esa.int/project/exomars-rosalind-franklin-rfm/).
- **Enunciado del desafío:** texto proporcionado por el equipo, *Identify Earth Locations that Analog the Permanent Moon Base Locations and Mars* (NASA Space Apps Challenge 2026). El objetivo evaluable es una ubicación terrestre caracterizada, presentada en una herramienta o visualización.

---

## Prospección mundial de sitios terrestres para analogías marcianas

**NASA Space Apps Challenge 2026 · Línea Marte**  
**14 de noviembre de 2026 · Versión corregida de la lista corta**

**Insumos:** [caracterización de Arcadia–Amazonis, Jezero, Gale y Oxia](#caracterización-de-regiones-de-marte-para-buscar-análogos-terrestres) y [preguntas A1–O3](#paso-1--preguntas-de-exploración-marciana-que-guiarán-la-búsqueda-de-análogos-terrestres). Se eliminaron las preferencias geográficas de la primera búsqueda. **El resultado buscado son ubicaciones terrestres caracterizadas; Marte proporciona las preguntas y los comparadores.**

### 1. Método y alcance de las afirmaciones

Buscamos por proceso y tarea: hielo y polígonos (Arcadia), desembocaduras y facies deltaicas (Jezero), cambios lacustre–eólico (Gale) y origen de arcillas en roca hospedante (Oxia). Para cada candidato distinguimos **medición publicada**, **hipótesis de analogía** y **prueba pendiente**. Que un sitio aparezca en esta lista no implica que sea único, desconocido, accesible para tomar muestras o ya validado con datos satelitales procesados por el equipo. «Original» significará un uso específico insuficientemente probado frente a comparadores, sujeto a revisión bibliográfica.

| Evidencia | Valor y límite |
|---|---|
| Perfil, facies, mineralogía o sondeo medido | Verifica un atributo local; no caracteriza automáticamente toda una región. |
| Imágenes, radar y DEM | Delimitan formas, tiempos y escalas; una señal de radar no verifica por sí sola la composición o profundidad del hielo. |
| Interpretación Tierra–Marte | Requiere propiedad compartida, escala compatible, prueba independiente y diferencias físicas explícitas. |

### 2. Lista corta mundial, ordenada por pregunta

| Sector terrestre | Pregunta marciana | Lo que está documentado | Hipótesis y estado |
|---|---|---|---|
| **Saskylakh, campo poligonal junto al aeródromo, Yakutia (Rusia)** | **A2/A3** terreno poligonal y cambio; **A1** condicional | Estudio de **12,84 km²** centrado aproximadamente en **71,95° N, 114,10° E** con polígonos de centro bajo/alto, Sentinel-1 InSAR, Landsat y JAXA AW3D30 [1]. | Comparar visibilidad de obstáculos a distintas resoluciones y deformación. Para detección de hielo A1 faltan profundidad y controles de subsuelo **en puntos georreferenciados**. |
| **Delta de Lake Yamma Yamma, Queensland (Australia)** | **J1**, secundariamente O2 geométrico | Lago efímero ~**20 × 40 km**, delta migrante, granulometría, hidrología, imágenes y DEM [2, 3]. | Ensayar si interpretación orbital elige facies adecuadas de una desembocadura efímera; validación posible contra campo publicado. |
| **Perfil de Bhallil, Atlas Medio (Marruecos)** | **O1/J2** minerales y origen de alteración | Metabasalto y saprolita con smectita/interestratificados clorita–smectita; petrografía, DRX, Mössbauer y estados Fe²⁺/Fe³⁺ por nivel [4]. | Probar cómo un mismo mineral oculta distintas historias de alteración. Falta localizar coordenada y extensión cartografiable del perfil. |
| **Williams Point, Kati Thanda–Lake Eyre (Australia)** | **G1**, G2 condicional | Columna ~**15 m**: base lacustre, **5–6 m** fluvio-lacustres, ~**0,5 m** litoral, **6 m** eólicos; análisis mineralógicos y cronología [5]. | Comparar lectura de unidades húmedas y eólicas, sin afirmar coincidencia exacta de la transición arcilla–sulfato de Gale. Parque con acceso restringido [6]. |
| **Perfiles periféricos de Salada de Chiprana (España)** | **G1/G2** | Paleosuelos y facies lacustres/eólicas, incluyendo paleosuelo sobre sedimento eólico datado **322,2 ± 21,6 ka** [7]. | Control independiente para Williams Point; falta comprobar minerales por estrato. Reserva natural [8]. |
| **Sondeos de Aucanquilcha (Chile)** | **A1/A3**, condicional | Perforación y termometría en estudio multisitio altoandino; punto ~5.300 m [9]. | Verificar sondeo preciso, hielo real y control seco antes de proponer ensayo de detección. Ojos del Salado ya es análogo publicado [10]. |
| **Depósitos marginales de Laguna Miscanti (Chile)** | **J1/G1**, condicional | Facies lacustres y abanicos; testigo de **7,95 m** y registro ~22 ka [11, 12]. | Un abanico no es un delta sin facies y conexión demostradas; reserva protegida [13]. |
| **Tobas Colbún de Quinamávida (Chile)** | **O1/J2**, parcial | Tobas alteradas a zeolitas, con smectita variable [14]. | Caso para estudiar falsas clasificaciones minerales; zeolitas dominantes impiden llamarlo análogo directo de arcillas Fe/Mg de Oxia. |

**No hay cuota por continente ni puntuación total única.** Los cuatro primeros sectores son las hipótesis más interesantes para **tareas distintas**; los siguientes sirven de alternativas y controles. Las coordenadas de Saskylakh se refieren al área de estudio, no a perforaciones. No se han validado todavía las coordenadas de afloramiento del resto.

### 3. Pruebas que harían útiles los cuatro candidatos principales

#### Saskylakh: de una llanura orbital a obstáculos y deformación

El estudio de Wang y colaboradores (2023) distingue polígonos de centro bajo y alto, lagunas termokársticas y transectos aproximados de **9 y 6,8 km**. Informan contenido regional de hielo **>40 % en volumen** y capa activa próxima a 1 m a partir de referencias previas, y analizan deformación en **2018–2019** con Sentinel-1. Usaron Landsat y JAXA AW3D30 [1]. Es un sector concreto, no «toda Siberia».

**Ensayo A2:** delimitar campo, distinguir polígonos, agua y surcos en imagen de alta resolución, luego reducir a píxeles de 30 m; cuantificar obstáculos que desaparecen y errores de trazado de ruta. **Ensayo A3:** comparar cambios temporales y mecanismos de degradación; la fusión y circulación de agua terrestres no se extrapolan automáticamente a Marte. **A1 exige sondeos/exposiciones locales** y profundidad del hielo: el porcentaje regional y la deformación InSAR no miden el techo de hielo bajo cada celda.

**Prueba de descarte:** sin cartografía fina abierta para validar y sin series reproducibles, relegarlo a comparador. Un ensayo de campo en Yakutia exige logística y permisos aún no investigados. El conocido Axel Heiberg [15] sirve de control de analogía criogénica.

#### Lake Yamma Yamma: una desembocadura real para Jezero

Mann y Amos (2022) estudiaron un lago efímero de ~20 × 40 km, ~750 km aguas arriba y ~90 m por encima de Kati Thanda–Lake Eyre, cuyo delta principal migra al noroeste. Reunieron granulometría, facies de campo, imágenes, frecuencia de inundación, hidrología y elevación [2]. Su tesis precedente documenta desembocaduras terminales, dunas y depósitos de crecida [3]. Queensland indica que se llena por completo aproximadamente **cada 25–30 años** [16].

**Ensayo J1:** trazar canal–entrada–delta–lago en imágenes y elevación, seleccionar hipotéticas muestras por apariencia orbital, y contrastar la clasificación contra facies publicadas. Para O2 se puede contrastar la geometría de canales, sin asumir que sean equivalentes a crestas invertidas de Oxia. **No representa** carbonatos, material ígneo de Jezero ni condiciones de Marte actual.

**Novedad delimitada:** ya está estudiado como análogo sedimentario de otra cuenca [3], y NASA llamó análogo planetario al **sistema regional de Cooper Creek**, que fluye hacia Yamma Yamma [17]. No presentarlo como sitio descubierto por nosotros. La propuesta propia es una evaluación reproducible de **elección de facies y falsos positivos en un delta seco**. Acceso/tenencia y valores ecológicos/culturales deben verificarse antes de cualquier campo [16].

#### Bhallil: misma señal arcillosa, distinto proceso

Dekayir y colaboradores (2002) describieron metabasalto triásico y saprolita; smectita y clorita–smectita pueden aparecer en ambos. Con petrografía, difracción de rayos X y Mössbauer distinguen niveles de hierro mayoritariamente ferroso, parcialmente oxidado y oxidado [4]. Existe figura de situación, pero **no se extrajeron coordenadas del perfil**.

**Ensayo O1/J2:** hacer una predicción con cartografía o espectro de superficie y revelar después el perfil mineralógico y estado de hierro. Pregunta: ¿se confunde roca previamente alterada con meteorización posterior? La utilidad está en el **proceso de inferencia**, no en afirmar que la composición completa de Bhallil sea la de Oxia. Murrin Murrin ya fue comparado explícitamente con Nili Fossae [18], y Otago/Granby se estudiaron para Oxia [19]: servirán de contraste. **Descartar como caso satelital** si el afloramiento es demasiado pequeño o la ubicación no se puede verificar.

#### Williams Point: sucesión estratigráfica para Gale

Cohen y colaboradores (2022) reexaminaron un acantilado de ~15 m en el borde sur de Madigan Gulf: capas lacustres basales, 5–6 m fluvio-lacustres, ~0,5 m de playa/costa y 6 m eólicos. Emplearon excavación, microfacies, DRX/FRX, isótopos y OSL; reportan fases lacustres ~230–131 ka, fluvio-lacustres ~86 ka y sedimento eólico yesífero ~49 ka [5]. Estas son edades terrestres, sin equivalencia cronológica con Gale.

**Ensayo G1:** clasificar capas y contactos de imágenes/perfiles sin revelar interpretación, después contrastar con mediciones del artículo. Para **G2** hay que verificar si el yeso es deposicional, reciclado o diagenético por estrato; la columna **no reproduce automáticamente** el paso arcilla–sulfato de Gale.

**Acceso:** Kati Thanda–Lake Eyre National Park es gestionado con pueblos Arabana y Dieri. Se llega a miradores por rutas designadas, pero no se permite el acceso recreativo al lecho; esto **no prueba** que Williams Point sea accesible [6]. Inicialmente debe ser ficha digital. Trabajo sobre el afloramiento requeriría autorización específica.

### 4. Casos secundarios y comparadores ya conocidos

- **Chiprana, España:** replicar G1 con paleosuelos y sedimentos lacustres/eólicos datados. Reserva Natural Dirigida; no inferir permiso para muestreo por poder visualizarla [7, 8].
- **Aucanquilcha, Chile:** sirve para A1 **solo** si un sondeo localizado muestra hielo y profundidad comprobados y otro ofrece control seco. Permafrost no implica hielo explotable en el punto elegido [9]. Ojos del Salado es control altoandino preexistente [10].
- **Miscanti, Chile:** comprobar con mapas y secciones si los abanicos publicados se conectan con facies lacustres; el testigo no valida por sí mismo un delta expuesto [11–13].
- **Quinamávida, Chile:** contraste negativo de espectros/minerales; no etiquetar como Oxia mineralógico porque las zeolitas predominan [14, 19].

| Análogo conocido | Papel en la comparación |
|---|---|
| **Qaidam occidental, China** [20] | Referencia de estudios de ambientes áridos; comparar preguntas concretas, no desiertos completos. |
| **Lago Salda, Turquía** [21] | Control carbonatado para Jezero, diferente al ensayo de facies de Yamma Yamma. |
| **Murrin Murrin, Australia** [18] | Perfil ya relacionado con filosilicatos marcianos, contraste directo de Bhallil. |
| **Otago/Granby** [19] | Controles mineralógicos publicados para Oxia. |
| **Axel Heiberg, Canadá** [15] | Control criogénico de formas ya descritas como análogos. |
| **Ojos del Salado** [10] | Control de investigaciones altoandinas, evita atribuir novedad geográfica a Aucanquilcha. |

Una búsqueda preliminar de topónimos y «Mars analog» no demuestra ausencia de estudios anteriores. Antes de presentar novedad al jurado hay que revisar también variantes del nombre, tesis y artículos locales. En particular, **Cooper Creek ya figura como analogía planetaria en NASA** [17].

### 5. Datos abiertos y secuencia ejecutable

| Tarea | Repositorios/productos | Resultado y límite |
|---|---|---|
| Delimitar cuencas, delta y polígonos | Artículos con figuras/coordenadas [1–5]; NASA **Earthdata/NASADEM** donde cubra [22]; **JAXA AW3D30** [23] | DEM de decenas de metros para contexto; no resuelve láminas ni microrelieve de rover. |
| Ver agua/inundación y cambios | NASA Landsat/Worldview; ESA **Sentinel-2** [24] | Series húmedo/seco y cobertura; nubes, sales y sombras pueden confundirse. |
| Deformación de Saskylakh | ESA **Sentinel-1**, Landsat, AW3D30 como en [1] | InSAR documenta desplazamiento relativo bajo condiciones de coherencia; no identifica profundidad o pureza del hielo. |
| Materiales/arcillas | DRX, petrografía, Mössbauer de [4, 5, 7, 14], mapas geológicos; espectros remotos solo donde la escala alcance | Sentinel-2 no diagnostica por sí solo la especie ni el origen de una arcilla. |
| Condiciones y uso | Instituciones de parques [6, 8, 13, 16] | Separar consulta digital, visita pública y muestreo con permiso. |

**Próxima entrega comprobable:** dos fichas de **procesos distintos** con polígono GeoJSON, coordenadas y su procedencia, imagen/DEM y al menos una capa temporal o geológica procesada, medida terrestre independiente, unidad marciana comparada, control conocido y una predicción susceptible de ser refutada. Empezar con **Yamma Yamma (J1)** y **Saskylakh (A2/A3)** por su expresividad cartográfica; **Bhallil (O1)** tras ubicar el perfil, y **Williams Point (G1)** si hay cartografía de afloramiento suficiente. Elegir por disponibilidad real de datos al ejecutar la prueba.

### 6. Cómo se verá ante el jurado

| Criterio comunicado | Evidencia que mostrar |
|---|---|
| **Impacto** | Catálogo reutilizable que ayude a escoger un análogo según objetivo, con datos y límites verificables. |
| **Creatividad** | Identificar fallos reales de inferencia: forma deltaica mal clasificada, mineral igual de origen distinto, hielo inferido de relieve. |
| **Validez** | Predicciones orbitales confrontadas con facies, mineralogía, sondeos o cartografía publicados; medidas con escala e incertidumbre. |
| **Relevancia** | Ubicaciones de la **Tierra** caracterizadas para una pregunta de Marte, sin convertir la lista de regiones marcianas en producto final. |
| **Presentación** | Mapa filtrable por pregunta, atributo, evidencia, acceso y ruptura de analogía; ficha que separa dato, inferencia y pendiente. |

### Fuentes primarias y oficiales

1. Wang et al. (2023), [Saskylakh y deformación InSAR](https://doi.org/10.3390/rs15051335), *Remote Sensing* 15, 1335. El dato regional de hielo y capa activa remite a referencias del artículo.
2. Mann y Amos (2022), [sedimentología de Lake Yamma Yamma](https://doi.org/10.1080/03721426.2022.2027649), estudio de campo, satélite, inundación y DEM.
3. Mann (2017), [tesis doctoral, Universidad de Adelaide](https://digital.library.adelaide.edu.au/items/8bda2080-2ba5-4846-b970-7f25808a9926/full), depósitos terminales y comparación sedimentaria.
4. Dekayir et al. (2002), [perfil de alteración de Bhallil](https://doi.org/10.1016/S1631-0713(02)01829-1), *Comptes Rendus Geoscience* 334.
5. Cohen et al. (2022), [secuencia de Williams Point](https://digital.library.adelaide.edu.au/items/52c0c260-3351-4916-8dc8-a931281d04aa), investigación original y cronología.
6. South Australia National Parks, [Kati Thanda–Lake Eyre National Park](https://www.parks.sa.gov.au/parks/kati-thanda-lake-eyre-national-park), administración y acceso.
7. Tierra et al. (2026), [paleosuelos de Salada de Chiprana](https://doi.org/10.1016/j.catena.2026.110058), *Catena*.
8. Gobierno de Aragón, [Reserva Natural Dirigida Saladas de Chiprana](https://www.aragon.es/-/reserva-natural-dirigida-de-las-saladas-de-chiprana).
9. Yoshikawa et al. (2025), [permafrost de Andes áridos](https://doi.org/10.1080/15230430.2025.2532202), estudio de múltiples montañas.
10. Nagy et al., [Ojos del Salado y analogía térmica](https://doi.org/10.1089/ast.2018.2021).
11. Valero-Garcés et al. (1999), [facies lacustres del Altiplano](https://www.sciencedirect.com/science/article/abs/pii/S0031018299000188).
12. Grosjean et al. (2001), [testigo de Miscanti](https://www.sciencedirect.com/science/article/pii/S0921818100000631).
13. CONAF, [Reserva Nacional Los Flamencos](https://www.conaf.cl/parque_nacionales/reserva-nacional-los-flamencos/).
14. Bascuñán et al. (2007), [tobas zeolitizadas en Quinamávida](https://www.cambridge.org/core/journals/clays-and-clay-minerals/article/abs/zeolitization-of-tuffs-at-quinamavida-central-southern-chile/2FEAC4DB7907E913D97703DD4EF159A6).
15. Hibbard et al. (2022), [Axel Heiberg, formas análogas](https://www.hou.usra.edu/meetings/lpsc2022/pdf/2551.pdf).
16. Queensland Government, [Cooper Creek y Lake Yamma Yamma](https://wetlandinfo.detsi.qld.gov.au/wetlands/ecology/processes-systems/water/catchment-stories/lake-eyre-basin/cooper-creek/), funcionamiento y valores del humedal.
17. NASA Earth Observatory, [*Cooper Creek, Australia*](https://science.nasa.gov/earth/earth-observatory/cooper-creek-australia-147046/), analogía planetaria regional ya conocida.
18. Carter et al., [Murrin Murrin y Nili Fossae](https://www.sciencedirect.com/science/article/abs/pii/S0019103511003496), comparación previa.
19. Krzesińska et al. (2021), [Otago/Granby como controles de Oxia](https://pubmed.ncbi.nlm.nih.gov/34406809/).
20. Anglés y Li (2017), [Qaidam occidental](https://doi.org/10.1002/2017JE005293).
21. NASA Earth Observatory, [Lago Salda y Jezero](https://science.nasa.gov/earth/earth-observatory/jez-like-mars-147041/).
22. NASA, [Earthdata Search](https://search.earthdata.nasa.gov/).
23. JAXA, [AW3D30](https://www.eorc.jaxa.jp/ALOS/en/aw3d30/data/index.htm).
24. ESA, [Copernicus Sentinel-2](https://documentation.dataspace.copernicus.eu/Data/SentinelMissions/Sentinel2.html); [Sentinel-1](https://documentation.dataspace.copernicus.eu/Data/Sentinel1.html).

**Estado final de esta etapa:** revisión bibliográfica comparativa mundial; aún **no** se descargaron ni procesaron capas sobre polígonos propios, verificaron todas las coordenadas de afloramiento ni obtuvieron permisos. Ningún sitio se presenta como análogo validado o descubrimiento absoluto.
