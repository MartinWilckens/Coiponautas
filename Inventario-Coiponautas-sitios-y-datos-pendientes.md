# Inventario de sitios y datos pendientes · Coiponautas

Este listado cubre las **78 fichas del HTML** publicado. Una ficha puede representar un sector, una instalación o una campaña. Se conserva el nombre de cada entrada para poder cruzarla con el catálogo. [Atlas auditado](https://github.com/MartinWilckens/Coiponautas/blob/80b0dbea8d8237ca7dcd7414b1451286d659c3b0/Coiponautas-Atlas-Interactivo.html)

| Indicador | Fichas |
| --- | ---: |
| Candidatos de terreno | 10 |
| Antecedentes con ficha propia (LUNA y PANGAEA) | 2 |
| Entradas de la compilación histórica | 66 |
| Geometría incorporada al atlas | 4 |
| Algún dato específico estructurado además de la descripción del entorno | 7 |
| Dosis de radiación ionizante estructurada | 0 |
| Imagen preparada como campo de la ficha para comparar | 0 |

## Qué conviene completar en cada ficha

Para cada sitio, identificar **tarea, sector, coordenadas, permiso de acceso y una imagen del sector** con autor, fuente y licencia. Para cada parámetro pertinente, guardar **valor, unidad, fuente, año o periodo, método, escala y página o figura**. La pendiente, rugosidad, agua, hielo, polvo o radiación se registran según el ensayo. Si un dato es pertinente y falta, queda pendiente. En un recinto controlado, se registran las condiciones del ensayo.

El atlas usa temperatura, humedad y presión regionales de la celda de 4° que corresponde a la ubicación del sitio. En las fichas se identifica esa procedencia por separado de las observaciones del terreno. [CSV del equipo](https://github.com/MartinWilckens/Coiponautas/blob/1298dd85743548ba6a0edaad75a028fedd1c8d7e/database.csv)

## Datos adicionales que faltan para hacer la comparación

| Bloque | Qué falta levantar | Evidencia que permite comparar |
| --- | --- | --- |
| Sector y tamaño | Punto, polígono o ruta, altitud, área utilizable y extensión del estudio. | Geometría en WGS84, escala original, incertidumbre y descripción de lo que representa el punto. |
| Relieve y movilidad | Pendiente media y máxima, rugosidad, tamaño de obstáculos, sustrato y tramos transitables. | Perfil o DEM con resolución indicada, recorrido y observaciones de campo cuando existan. |
| Geología y perforación | Litología, mineralogía, granulometría, estratos, dureza o resistencia, profundidad de perforación y muestras de control. | Mapa geológico, registro del sondeo o informe. Ubicar cada muestra y su profundidad. |
| Agua y sales | Estado, extensión, duración, salinidad y restricciones de acceso o de muestreo. | Series o imágenes fechadas y análisis por punto. Registrar el periodo seco y el húmedo cuando corresponda. |
| Hielo y suelo congelado | Distinguir nieve o hielo superficial, hielo enterrado y permafrost. Registrar profundidad, fracción, espesor y estacionalidad. | Sondeo, muestra o interpretación geofísica con método, incertidumbre y control seco. |
| Condiciones ambientales | Temperatura, humedad, presión, viento, precipitación, episodios de polvo e iluminación útil. | Serie local o producto regional con periodo, resolución y procedencia. Conservar escala horaria o estacional cuando afecte al ensayo. |
| Radiación ionizante | Dosis por punto medido, altura del sensor, periodo, instrumento y condiciones de blindaje. | Registrar el tipo de magnitud y su unidad. El repositorio aporta referencias de Luna, Marte y Tierra, y queda pendiente vincular mediciones a cada candidato terrestre. [Compilación de radiación del equipo](https://github.com/MartinWilckens/Coiponautas/blob/7ab64bf33bafcc1fa3f7afc700e5c15ba080666a/luvsichexalogy.md#datos-de-radiaci%C3%B3n-en-la-luna-y-marte) |
| Acceso y operación | Titular del terreno, temporadas de acceso, permisos por actividad, rutas, comunicaciones y soporte de emergencia. | Autoridad, norma o contacto, con fecha de comprobación y cobertura espacial. |
| Imágenes para la comparación | Vista general y detalle a escala del sector, afloramiento, ruta o recinto. | Imagen con ubicación, fecha, autor, licencia y fuente. Indicar si corresponde al punto exacto o a su contexto. |
| Resultado del ensayo | Tarea, instrumento, condiciones de ejecución, resultado observado y criterio de éxito. | Informe original del operador o estudio, con página, figura y sector. Separar sitio físico y nombre de campaña. |

En cada campo usaremos **documentado**, **regional**, **pendiente** o **no aplica**. Un dato regional se puede usar para explorar y debe indicar su resolución. Un dato documentado en otro sector del mismo lugar necesita su propia ubicación. Para subir una ficha nueva al atlas, el mínimo propuesto es nombre, coordenadas o sector por confirmar, tarea, una fuente verificable y una imagen acreditada si está disponible.

## Candidatos y antecedentes con ficha propia

### Saskylakh · Rusia

**Uso o ensayo** — Hielo enterrado y movilidad.

- **Ubicación** — Ubicación regional aproximada (71.95000°, 114.10000°). [Wang et al. (2023), Saskylakh](https://doi.org/10.3390/rs15051335)
- **Clima regional** — -12,31 °C, 94,53 % de humedad relativa, 99,4 kPa. Centro de celda 70°, 116°. [CSV](https://github.com/MartinWilckens/Coiponautas/blob/1298dd85743548ba6a0edaad75a028fedd1c8d7e/database.csv)
- **Entorno** — Terreno periglacial. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [Wang et al. (2023), Saskylakh](https://doi.org/10.3390/rs15051335)
- **Superficie** — 12,84 km². Área publicada del estudio · Área de estudio · Área total del estudio. [Wang et al. (2023), Saskylakh](https://doi.org/10.3390/rs15051335)
- **Terreno poligonal** — Sí. Interpretación de imágenes · Figuras de morfología · Campo poligonal. [Wang et al. (2023), Saskylakh](https://doi.org/10.3390/rs15051335)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [Wang et al. (2023), Saskylakh](https://doi.org/10.3390/rs15051335)
- **Completar primero** — Perímetro del campo poligonal, profundidad y presencia de hielo con sondeos y controles secos, pendiente, rugosidad y rutas transitables.
- **Mediciones y evidencias adicionales** — Registrar la resolución y fecha del relieve y de las imágenes de los polígonos. Medir profundidad de deshielo estacional y vincularla a perfiles y puntos de humedad.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Lake Yamma Yamma · Australia

**Uso o ensayo** — Muestreo sedimentario y navegación.

- **Ubicación** — Límite oficial del humedal (polígono incorporado). [Queensland WetlandInfo, inventario DIWA](https://wetlandinfo.detsi.qld.gov.au/wetlands/facts-maps/diwa-wetland-lake-yamma-yamma/)
- **Clima regional** — 25,56 °C, 36,93 % de humedad relativa, 100,78 kPa. Centro de celda -26°, 140°. [CSV](https://github.com/MartinWilckens/Coiponautas/blob/1298dd85743548ba6a0edaad75a028fedd1c8d7e/database.csv)
- **Entorno** — Delta y humedal efímero. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [Mann y Amos (2022), Lake Yamma Yamma](https://doi.org/10.1080/03721426.2022.2027649)
- **Superficie** — 866,14 km². Área publicada del inventario · Total area, 86.614 ha · Humedal DIWA. [Queensland WetlandInfo, inventario DIWA](https://wetlandinfo.detsi.qld.gov.au/wetlands/facts-maps/diwa-wetland-lake-yamma-yamma/)
- **Agua documentada** — Estacional. Humedal que se inunda de forma intermitente según el inventario DIWA · Humedal DIWA. [Queensland WetlandInfo, inventario DIWA](https://wetlandinfo.detsi.qld.gov.au/wetlands/facts-maps/diwa-wetland-lake-yamma-yamma/)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [Mann y Amos (2022), Lake Yamma Yamma](https://doi.org/10.1080/03721426.2022.2027649)
- **Completar primero** — Polígono del delta nororiental, fechas húmedas y secas con su extensión de agua, pendiente, granulometría y facies del sector.
- **Mediciones y evidencias adicionales** — Añadir superficie inundada por fecha y ubicación de cada muestra de sedimento. Registrar microrelieve de la ruta y estado del firme entre campañas.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Bhallil · Marruecos

**Uso o ensayo** — Muestreo de perfiles de alteración.

- **Ubicación** — falta incorporar la geometría del sector. El filtro climático queda pendiente.
- **Entorno** — Perfil de alteración. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [Dekayir et al. (2002), Bhallil](https://doi.org/10.1016/S1631-0713(02)01829-1)
- **Minerales** — smectita, clorita-smectita. DRX y petrografía · Resultados mineralógicos · Muestras del perfil vertical. [Dekayir et al. (2002), Bhallil](https://doi.org/10.1016/S1631-0713(02)01829-1)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [Dekayir et al. (2002), Bhallil](https://doi.org/10.1016/S1631-0713(02)01829-1)
- **Completar primero** — Coordenadas del perfil y afloramientos, espesor de los niveles, mineralogía por muestra y acceso.
- **Mediciones y evidencias adicionales** — Delimitar superficie disponible para trabajo de campo. Añadir humedad, dureza y espesores por nivel con una escala visible en fotografías del perfil.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Williams Point · Australia

**Uso o ensayo** — Lectura de secuencias sedimentarias.

- **Ubicación** — Punto fotográfico de contexto (-29.03980°, 137.62840°). [Martin Struck, EGU Imaggeo, CC BY 3.0](https://imaggeo.egu.eu/view/3022/)
- **Clima regional** — 21,61 °C, 41,12 % de humedad relativa, 100,36 kPa. Centro de celda -30°, 136°. [CSV](https://github.com/MartinWilckens/Coiponautas/blob/1298dd85743548ba6a0edaad75a028fedd1c8d7e/database.csv)
- **Entorno** — Secuencia sedimentaria. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [Cohen et al. (2022), Williams Point](https://doi.org/10.1016/j.quascirev.2022.107635)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [Cohen et al. (2022), Williams Point](https://doi.org/10.1016/j.quascirev.2022.107635)
- **Completar primero** — Ubicación de la sección y muestras, coordenadas del afloramiento, espesores por nivel, mineralogía y granulometría.
- **Mediciones y evidencias adicionales** — Registrar orientación, continuidad lateral y accesibilidad de cada tramo. Etiquetar las imágenes con el contacto estratigráfico o la muestra a la que corresponden.
- **Imagen** — existe una fotografía de contexto enlazada. Falta una vista identificada del perfil específico. [Martin Struck, EGU Imaggeo, CC BY 3.0](https://imaggeo.egu.eu/view/3022/)

### Salada de Chiprana · España

**Uso o ensayo** — Muestreo lacustre y eólico.

- **Ubicación** — falta incorporar la geometría del sector. El filtro climático queda pendiente.
- **Entorno** — Lacustre y eólico. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [Tierra et al. (2026), paleosuelos de Chiprana](https://doi.org/10.1016/j.catena.2026.110058)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [Tierra et al. (2026), paleosuelos de Chiprana](https://doi.org/10.1016/j.catena.2026.110058)
- **Completar primero** — Ubicar perfiles de paleosuelos, delimitar facies, medir salinidad y granulometría, y comprobar permisos de muestreo.
- **Mediciones y evidencias adicionales** — Separar playas, dunas y paleosuelos en el mapa. Registrar nivel de agua, variación por estación y procedimiento usado para las medidas de salinidad.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Aucanquilcha · Chile

**Uso o ensayo** — Perforación y prospección de hielo.

- **Ubicación** — falta incorporar la geometría del sector. El filtro climático queda pendiente.
- **Entorno** — Alta montaña. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [Yoshikawa et al. (2025), Andes áridos](https://doi.org/10.1080/15230430.2025.2532202)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [Yoshikawa et al. (2025), Andes áridos](https://doi.org/10.1080/15230430.2025.2532202)
- **Completar primero** — Coordenadas del sondeo y del control seco, profundidad y fracción de hielo, condiciones del suelo y rutas de acceso.
- **Mediciones y evidencias adicionales** — Documentar el método y fecha de detección del hielo, espesor de cobertura seca, litología y resistencia de los materiales atravesados.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Laguna Miscanti · Chile

**Uso o ensayo** — Muestreo lacustre y depósitos marginales.

- **Ubicación** — falta incorporar la geometría del sector. El filtro climático queda pendiente.
- **Entorno** — Lago y depósitos marginales. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [Grosjean et al. (2001), testigo de Miscanti](https://www.sciencedirect.com/science/article/pii/S0921818100000631)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [Grosjean et al. (2001), testigo de Miscanti](https://www.sciencedirect.com/science/article/pii/S0921818100000631)
- **Completar primero** — Ubicar depósitos y transectos de orilla, medir granulometría y mineralogía, caracterizar estacionalidad del agua y verificar permisos.
- **Mediciones y evidencias adicionales** — Distinguir el lago del punto de extracción del testigo y de los perfiles de orilla. Añadir profundidad del agua, salinidad y posición de cada transecto.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Quinamávida · Chile

**Uso o ensayo** — Muestreo mineralógico.

- **Ubicación** — falta incorporar la geometría del sector. El filtro climático queda pendiente.
- **Entorno** — Tobas alteradas. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [Bascuñán et al. (2007), tobas zeolitizadas](https://www.cambridge.org/core/journals/clays-and-clay-minerals/article/abs/zeolitization-of-tuffs-at-quinamavida-central-southern-chile/2FEAC4DB7907E913D97703DD4EF159A6)
- **Minerales** — zeolitas, smectita. Caracterización mineralógica publicada · Mineralogía · Muestras de tobas. [Bascuñán et al. (2007), tobas zeolitizadas](https://www.cambridge.org/core/journals/clays-and-clay-minerals/article/abs/zeolitization-of-tuffs-at-quinamavida-central-southern-chile/2FEAC4DB7907E913D97703DD4EF159A6)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [Bascuñán et al. (2007), tobas zeolitizadas](https://www.cambridge.org/core/journals/clays-and-clay-minerals/article/abs/zeolitization-of-tuffs-at-quinamavida-central-southern-chile/2FEAC4DB7907E913D97703DD4EF159A6)
- **Completar primero** — Ubicar el perfil de tobas, cuantificar minerales por muestra, registrar estratigrafía, accesos y permiso de muestreo.
- **Mediciones y evidencias adicionales** — Separar toba fresca y alterada. Registrar proporciones minerales por intervalo, técnica analítica y granulometría de las muestras.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### LUNA · Colonia · Alemania

**Uso o ensayo** — Ensayos en instalación.

- **Ubicación** — falta incorporar la geometría del sector. El filtro climático queda pendiente.
- **Entorno** — Instalación de simulación. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [DLR, instalación LUNA](https://www.dlr.de/en/research-and-transfer/featured-topics/mission-moon/the-luna-moon-facility)
- **Superficie** — 0,0007 km². Descripción institucional · 700 m² de terreno · Área interior de simulante. [DLR, instalación LUNA](https://www.dlr.de/en/research-and-transfer/featured-topics/mission-moon/the-luna-moon-facility)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [DLR, instalación LUNA](https://www.dlr.de/en/research-and-transfer/featured-topics/mission-moon/the-luna-moon-facility)
- **Completar primero** — Ubicar la instalación en el mapa, delimitar el área de ensayo y documentar granulometría y densidad del simulante, parámetros controlados y acceso.
- **Mediciones y evidencias adicionales** — Registrar iluminación programada, humedad, capacidad de recrear pendientes y parámetros del simulante para cada tipo de prueba.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Lanzarote · PANGAEA · España

**Uso o ensayo** — Entrenamiento geológico.

- **Ubicación** — falta incorporar la geometría del sector. El filtro climático queda pendiente.
- **Entorno** — Terreno volcánico. Caracterización publicada recopilada por el equipo · Descripción del sitio · Sector documentado en la fuente. [ESA, PANGAEA en Lanzarote](https://www.esa.int/Newsroom/Press_Releases/Invitacion_a_medios_Entrenamiento_de_astronautas_PANGAEA_en_Lanzarote)
- **Acceso** — Acceso y permisos por actividad pendientes de comprobar. [ESA, PANGAEA en Lanzarote](https://www.esa.int/Newsroom/Press_Releases/Invitacion_a_medios_Entrenamiento_de_astronautas_PANGAEA_en_Lanzarote)
- **Completar primero** — Identificar ruta y sectores exactos del curso, pendiente, rugosidad, litología, actividad específica y permisos.
- **Mediciones y evidencias adicionales** — Documentar distancias y tiempos de recorrido, instrumentos utilizados, resultados de campo e imágenes georreferenciadas de los afloramientos.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Pali-Aike · Chile

**Uso o ensayo** — Movilidad y navegación volcánica.

- **Ubicación** — falta incorporar la geometría del sector. El filtro climático queda pendiente.
- **Pendiente** — 10–22 °. Cartografía de Sernageomin citada por neo.md · Piloto Pali-Aike · Pendientes hacia la base del cono. [Investigación lunar de Vicente · Pali-Aike](https://github.com/MartinWilckens/Coiponautas/blob/f6e9002d527cef8030672461d22f3a98174ef38f/neo.md)
- **Diámetro de cráter** — 160–180 m. Cartografía de Sernageomin citada por neo.md · Piloto Pali-Aike · Cráter cartografiado. [Investigación lunar de Vicente · Pali-Aike](https://github.com/MartinWilckens/Coiponautas/blob/f6e9002d527cef8030672461d22f3a98174ef38f/neo.md)
- **Completar primero** — Coordenadas del cono y la ruta, trazabilidad de pendiente y diámetro por sector, rugosidad, horizonte, contraste y acceso.
- **Mediciones y evidencias adicionales** — Registrar tamaño de obstáculos, continuidad del firme y método de medición del relieve. Asociar las fotos con el tramo recorrido y el cono identificado.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

### Chajnantor · sondeo B3 · Chile

**Uso o ensayo** — Prospección de hielo.

- **Ubicación** — Sondeo B3 (-22.99028°, -67.72889°). [Sondeo B3 y evidencia de permafrost · investigación de Vicente](https://github.com/MartinWilckens/Coiponautas/blob/1298dd85743548ba6a0edaad75a028fedd1c8d7e/neo.md#posible-solución--chajnantor-como-análogo-de-prospección-en-haworth)
- **Clima regional** — 6,08 °C, 28,11 % de humedad relativa, 60,88 kPa. Centro de celda -22°, -68°. [CSV](https://github.com/MartinWilckens/Coiponautas/blob/1298dd85743548ba6a0edaad75a028fedd1c8d7e/database.csv)
- **Hielo documentado** — Presente. Sondeo en suelo volcánico. El estudio estimó 46 % de hielo por volumen hasta 2 m en B3. · sondeo B3. [Sondeo B3 y evidencia de permafrost · investigación de Vicente](https://github.com/MartinWilckens/Coiponautas/blob/1298dd85743548ba6a0edaad75a028fedd1c8d7e/neo.md#posible-solución--chajnantor-como-análogo-de-prospección-en-haworth)
- **Altitud** — 5075 m. Altitud aproximada reportada · sondeo B3. [Sondeo B3 y evidencia de permafrost · investigación de Vicente](https://github.com/MartinWilckens/Coiponautas/blob/1298dd85743548ba6a0edaad75a028fedd1c8d7e/neo.md#posible-solución--chajnantor-como-análogo-de-prospección-en-haworth)
- **Completar primero** — Incorporar el 46 % de hielo hasta 2 m como valor estructurado del sondeo, delimitar su alcance, documentar controles B4/B5, pendiente, rugosidad y acceso.
- **Mediciones y evidencias adicionales** — Vincular la altitud y los perfiles de temperatura del suelo a cada sondeo. Registrar material suprayacente, método de estimación del hielo y condiciones de acceso para los instrumentos.
- **Imagen** — preparar una vista del sector con fuente y licencia para la comparación.

## Orden práctico para cerrar vacíos

1. **Geometría y procedencia.** Incorporar la ubicación del cono y la ruta de Pali-Aike, los sondeos de Aucanquilcha, el perfil de Bhallil y los depósitos concretos de Miscanti y Chiprana. Afinar el polígono de Yamma Yamma y el punto de Williams Point hasta la escala de la tarea.
2. **Mediciones vinculadas.** Estructurar los sondeos de Chajnantor y sus controles, el agua estacional de Yamma Yamma y las mediciones de relieve de Saskylakh y Pali-Aike. Registrar fuente y localizador de cada parámetro.
3. **Comparación visual.** Seleccionar imágenes acreditadas de esos sectores y preparar una vista comparable por tarea. En las campañas históricas, empezar por aquellas con sectores y protocolos bien identificados.
4. **Fichas nuevas.** Asignar identificadores separados para sitio, sector y campaña. Revisar primero Devon, Lanzarote, Colonia, Houston y Moscú, donde la documentación puede describir campañas distintas dentro del mismo lugar.

## Inventario histórico de campañas

Las 66 entradas tienen descripción de su campaña o entorno y enlazan a la compilación. Para cada entrada falta identificar el sector exacto, enlazar la fuente original, agregar una imagen acreditada e incorporar los parámetros de la tabla. Las coincidencias de nombre se conservan porque pueden corresponder a campañas distintas. [Inventario de Joaco · compilación del equipo](https://github.com/MartinWilckens/Coiponautas/blob/f6e9002d527cef8030672461d22f3a98174ef38f/luvsichexalogy.md)

### Desiertos, regiones áridas y terrenos geológicos (22)

| Entrada | Campaña o uso descrito | Datos que faltan para compararla |
| --- | --- | --- |
| 1. Hanksville / San Rafael Swell, Utah, Estados Unidos | Mars Desert Research Station (MDRS). Grupos/programas: The Mars Society; crews universitarias e internacionales; campañas como AustroMars y Hypatia. | Diferenciar la estación MDRS del sector de campo de San Rafael Swell. Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Obtener el trazado de las salidas MDRS y separar los afloramientos por campaña. |
| 2. Devon Island, Nunavut, Canadá | Haughton impact crater y entorno del Ártico alto. Grupos/programas: Haughton-Mars Project (HMP), Mars Institute, NASA y colaboradores académicos. | Distinguir campaña y sector de las otras entradas de isla de Devon. Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Vincular las estaciones de muestreo del cráter Haughton con la cartografía de brechas de impacto. |
| 3. Devon Island, Nunavut, Canadá | Flashline Mars Arctic Research Station (FMARS). Grupos/programas: The Mars Society; crews internacionales y equipos universitarios. | Distinguir campaña y sector de las otras entradas de isla de Devon. Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Ubicar el hábitat FMARS y distinguir sus rutas de práctica de los transectos científicos. |
| 4. Desierto del Néguev / cráter Ramon, Israel | Mitzpe Ramon y Makhtesh Ramon. Grupos/programas: D-MARS (Desert Mars Analog Ramon Station); investigadores y universidades israelíes e internacionales. | Confirmar qué actividad y sector corresponden al cráter Ramon. Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Delimitar la zona de entrenamiento D-MARS y registrar las unidades de roca usadas en muestreo. |
| 5. Desierto de Dhofar, Omán | Región de Dhofar. Grupos/programas: Austrian Space Forum (OeWF), misión AMADEE-18. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Recuperar el itinerario de AMADEE-18 y la ubicación de cada ensayo de movilidad o instrumentos. |
| 6. Desierto del Néguev, Israel | Región de Mitzpe Ramon / Néguev. Grupos/programas: Austrian Space Forum (OeWF), misión AMADEE-20. | Cruzar con la entrada Néguev / cráter Ramon y conservar cada campaña identificada. Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Buscar las zonas de operación de AMADEE-20 y el alcance de comunicaciones durante el ensayo. |
| 7. Monte Ararat, Armenia | Región del volcán Ararat. Grupos/programas: Austrian Space Forum (OeWF), misión AMADEE-24. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Registrar desnivel, firme y exposición de las rutas de AMADEE-24. |
| 8. Sáhara septentrional, Marruecos | Campaña de terreno en el Sáhara. Grupos/programas: Austrian Space Forum (OeWF), misión MARS2013. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Vincular experimentos de MARS2013 con sus estaciones de medición y sus condiciones de polvo y viento. |
| 9. Arkaroola y Flinders Ranges, Australia Meridional | Arkaroola Wilderness Sanctuary y alrededores. Grupos/programas: Mars Society Australia (MSA); expediciones Jarntimarra, Spaceward Bound Australia y Mars Robot Challenge. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Separar el sector de la prueba robótica de los recorridos geológicos en Arkaroola. |
| 10. Arkaringa / Painted Desert / Coober Pedy, Australia Meridional | Paisajes áridos y depósitos sedimentarios. Grupos/programas: Mars Society Australia; expedición Jarntimarra-1 y campañas de selección de análogos. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Ubicar perfiles estratigráficos y muestras por localidad de la expedición Jarntimarra-1. |
| 11. Woomera y Moon Plain, Australia Meridional | Región de Woomera y llanuras cercanas. Grupos/programas: Mars Society Australia; expedición Jarntimarra-1. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Delimitar la llanura ensayada, registrar continuidad del firme y confirmar restricciones de acceso. |
| 12. Pilbara y Shark Bay, Australia Occidental | Regiones con estromatolitos y registros geológicos antiguos. Grupos/programas: Mars Society Australia y NASA Spaceward Bound Australia 2011. | Separar Pilbara y Shark Bay si se usaron para actividades distintas. Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Vincular cada observación de estromatolitos con su ambiente, escala y transecto. |
| 13. Marree, Reedy Springs y Lake Eyre, Australia Meridional | Terrenos áridos, salinos y abanicos aluviales. Grupos/programas: Mars Society Australia / NASA Spaceward Bound Australia 2009. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Distinguir manantiales, abanicos y salares. Registrar salinidad y superficie inundada por periodo. |
| 14. Cuenca de Qaidam, Qinghai, China | Desierto de gran altitud, salares y depósitos evaporíticos. Grupos/programas: Equipos científicos chinos e internacionales; estudios geomorfológicos y astrobiológicos de análogo marciano. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Delimitar el salar o cuenca específica y ligar las muestras de sales a la cartografía de facies. |
| 15. Jinchang, provincia de Gansu, China | China Mars Simulation Base / C-Space. Grupos/programas: Iniciativa china de simulación y divulgación; actividades educativas y ensayos relacionados con exploración marciana. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Separar el recinto C-Space de cualquier sector exterior y documentar el equipamiento empleado. |
| 16. Desierto de Atacama, Chile | Sectores hiperáridos del norte de Chile, incluidos Yungay y otros sitios de estudio. Grupos/programas: NASA Ames y equipos de astrobiología; universidades y grupos de investigación internacionales. | Acotar la campaña en Atacama y cruzarla con los candidatos andinos ya fichados. Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Precisar las estaciones de Yungay y comparar muestras con perfiles de aridez y sales del mismo sector. |
| 17. Danakil Depression, Etiopía | Depresión de Danakil y ambientes hidrotermales/salinos. Grupos/programas: Europlanet 2020 RI y equipos internacionales de investigación de análogos planetarios. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Distinguir las zonas muestreadas del sistema hidrotermal y registrar pH, temperatura, salinidad y acceso. |
| 18. Lago Tirez, España | Laguna salina y entorno evaporítico. Grupos/programas: Europlanet 2020 RI; investigadores europeos e internacionales. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Fechar el estado de inundación o desecación de la laguna y vincular cada muestra de sales a su estación. |
| 19. Rio Tinto, Andalucía, España | Cuenca minera y sistema fluvial ácido. Grupos/programas: NASA/ESA y equipos de astrobiología; Europlanet; Centro de Astrobiología (CAB/INTA-CSIC); campañas MARTE. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Ubicar transectos de agua, sedimento y subsuelo. Documentar pH y química por punto. |
| 20. Ibn Battuta Centre y alrededores, Marruecos | Entornos desérticos del sur de Marruecos. Grupos/programas: Europlanet 2020 RI; investigadores de geología planetaria y astrobiología. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Ubicar los recorridos y afloramientos usados, además del propio centro de apoyo. |
| 21. Tirol / Kaunertal / Innsbruck-Seefeld, Austria | Valles alpinos, glaciares y terrenos de montaña. Grupos/programas: Austrian Space Forum (OeWF), campañas de prueba Aouda y AMADEE-15. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Asignar cada medición de pendiente y nieve a una ruta concreta del ensayo de traje. |
| 22. Dachstein, Austria | Cuevas de hielo del macizo Dachstein. Grupos/programas: Austrian Space Forum (OeWF), campaña de análogo de 2012. | Litología, granulometría, pendiente y polvo. Añadir salinidad o agua estacional si son parte del ensayo. Ubicar entrada y tramo de la cueva de hielo, y documentar espesor, seguridad y época del recorrido. |

### Terrenos volcánicos, islas y regiones de interés geológico (13)

| Entrada | Campaña o uso descrito | Datos que faltan para compararla |
| --- | --- | --- |
| 23. Mauna Loa, Hawái, Estados Unidos | Laderas y campos volcánicos. Grupos/programas: HI-SEAS; International MoonBase Alliance; equipos universitarios y de investigación. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Distinguir el recinto de HI-SEAS de las coladas y rutas exteriores. Registrar accesos del ensayo. |
| 24. Kīlauea / Mauna Ulu, Hawái, Estados Unidos | Campos de lava basáltica. Grupos/programas: NASA BASALT; NASA Ames; investigadores de astrobiología y geología planetaria. | Separar los sectores visitados en Kīlauea y Mauna Ulu. Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Vincular muestras de BASALT a edad y tipo de colada, y documentar trayectos de aproximación. |
| 25. Hawái, Estados Unidos | Diversos terrenos volcánicos de la isla de Hawái. Grupos/programas: NASA Spaceward Bound; PISCES (Pacific International Space Center for Exploration Systems); universidades. | Identificar isla, sector y campaña antes de cruzarlo con Mauna Loa o Kīlauea. Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Relacionar cada experimento de PISCES o Spaceward Bound con su parcela y material de ensayo. |
| 26. Lanzarote, Islas Canarias, España | Campos volcánicos, tubos de lava y terrenos basálticos. Grupos/programas: ESA PANGAEA y PANGAEA-X; ESA; NASA y JAXA en actividades/campañas concretas; Europlanet. | Cruzar con la ficha Lanzarote · PANGAEA para identificar sectores o campañas compartidos. Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Separar rutas en coladas y tramos de tubos de lava, con fotogrametría cuando esté disponible. |
| 27. Tenerife, Islas Canarias, España | Terrenos volcánicos y ambientes de alta montaña. Grupos/programas: Campañas de geología planetaria y astrobiología europeas; actividades vinculadas a Europlanet y grupos universitarios. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Precisar la unidad volcánica y el gradiente altitudinal de cada sector visitado. |
| 28. Islandia | Desiertos volcánicos, campos de lava, glaciares y zonas geotérmicas. Grupos/programas: Europlanet; ESA y equipos académicos de geología planetaria; campañas de análogos lunares y marcianos. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Identificar para cada campaña la colada, glaciar o zona geotérmica y su relación con la tarea. |
| 29. Lofoten, Noruega | Terrenos de rocas antiguas y análogos de las tierras altas lunares. Grupos/programas: ESA PANGAEA; astronautas y especialistas en geología planetaria. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Localizar el afloramiento empleado en PANGAEA y documentar sus minerales y el relieve de acceso. |
| 30. Bletterbach / Dolomitas, Italia | Cañón sedimentario y secuencias estratigráficas. Grupos/programas: ESA PANGAEA; astronautas, geólogos planetarios y especialistas de exploración. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Ubicar el tramo del cañón y registrar espesor de estratos, litologías y puntos de muestreo. |
| 31. Cráter de impacto Nördlinger Ries, Baviera, Alemania | Estructuras y depósitos de impacto. Grupos/programas: ESA PANGAEA; históricamente, entrenamiento geológico de astronautas Apollo 14; investigadores planetarios. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Identificar afloramientos de brechas o materiales de impacto usados en cada campaña. |
| 32. Región de Bressanone, Italia | Afloramientos geológicos de los Alpes. Grupos/programas: Primeras ediciones de ESA PANGAEA. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Relacionar cada jornada de PANGAEA con la ruta, los afloramientos y los protocolos de muestreo. |
| 33. Isla de Svalbard, Noruega | Ambientes polares y periglaciares. Grupos/programas: Investigadores de geología planetaria y astrobiología; campañas científicas de análogos árticos. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Distinguir el sector periglacial, las unidades de terreno congelado y la época de trabajo de campo. |
| 34. Nuevo México, Estados Unidos | Campos volcánicos y volcanes en escudo. Grupos/programas: NASA y equipos de investigación planetaria; estudios comparativos con Venus y otros cuerpos. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Elegir el campo volcánico y el volcán específico. Identificar resolución de las medidas de relieve. |
| 35. California, Estados Unidos | Cuevas de lava y terrenos rocosos. Grupos/programas: NASA Planetary Analog Explorer; investigadores de tubos de lava lunares y reconocimiento geológico. | Sector de ensayo, litología, pendiente y rugosidad. Añadir profundidad o geometría de cavidades si corresponde. Precisar el tubo de lava y el tramo levantado, con sección, dimensiones y acceso autorizado. |

### Regiones polares y estaciones antárticas (6)

| Entrada | Campaña o uso descrito | Datos que faltan para compararla |
| --- | --- | --- |
| 36. Isla de Devon y Ártico canadiense | Desierto polar y cráter Haughton. Grupos/programas: Haughton-Mars Project; Mars Institute; NASA y universidades. | Cruzar con las otras dos entradas de Devon e identificar cada campaña. Separar estación y sector exterior. Documentar temperatura, nieve o hielo, acceso estacional y, si aplica, profundidad de hielo. Vincular la entrada regional con los mismos nombres de sectores y fuentes de las fichas de Devon. |
| 37. Estación Concordia, Antártida (Domo C) | Base franco-italiana en la meseta antártica. Grupos/programas: ESA; Agencia Espacial Italiana (ASI); Institut polaire français (IPEV); investigadores de fisiología, psicología y aislamiento. | Separar estación y sector exterior. Documentar temperatura, nieve o hielo, acceso estacional y, si aplica, profundidad de hielo. Separar los datos de aislamiento y operación de las mediciones exteriores de Domo C. |
| 38. Estación Neumayer III, Antártida | Base alemana en la plataforma de hielo Ekström. Grupos/programas: DLR, ESA y programas científicos antárticos; estudios de aislamiento y factores humanos. | Separar estación y sector exterior. Documentar temperatura, nieve o hielo, acceso estacional y, si aplica, profundidad de hielo. Documentar la zona de trabajo sobre la plataforma, acceso estacional y protocolos de aislamiento. |
| 39. Estación McMurdo, Antártida | Base logística y científica estadounidense. Grupos/programas: US Antarctic Program; NASA y grupos científicos que realizan campañas de campo en la Antártida. | Separar estación y sector exterior. Documentar temperatura, nieve o hielo, acceso estacional y, si aplica, profundidad de hielo. Distinguir la base de cada campaña de campo y vincular permisos a su ruta. |
| 40. Lake Untersee, Antártida | Lago subglacial/perennemente cubierto de hielo y entorno extremo. Grupos/programas: Investigadores de astrobiología y Mars Society Australia; estudios comparativos de ambientes extremos. | Separar estación y sector exterior. Documentar temperatura, nieve o hielo, acceso estacional y, si aplica, profundidad de hielo. Ubicar el área de muestreo del lago y registrar espesor del hielo, profundidad y química del agua. |
| 41. Alaska, Estados Unidos | Regiones glaciares y periglaciares. Grupos/programas: NASA y universidades; estudios de hielo, criogeología y análogos de cuerpos helados. | Separar estación y sector exterior. Documentar temperatura, nieve o hielo, acceso estacional y, si aplica, profundidad de hielo. Identificar el glaciar o campo periglacial y ligar los perfiles de hielo a su posición exacta. |

### Cuevas, ambientes subterráneos y estaciones confinadas (9)

| Entrada | Campaña o uso descrito | Datos que faltan para compararla |
| --- | --- | --- |
| 42. Sasso San Gottardo, Suiza | Fortaleza y galerías subterráneas del macizo del San Gotardo. Grupos/programas: Proyecto estudiantil internacional Asclepios I–VI; misiones lunares simuladas; WBA Eurohab (campaña 2025). | Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Añadir plano de las galerías asignadas a Asclepios, autonomía del recinto y cobertura de comunicaciones. |
| 43. Cuevas de Cerdeña, Italia | Sistemas cavernarios utilizados en entrenamiento subterráneo. Grupos/programas: ESA CAVES; astronautas de ESA y agencias asociadas. | Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Vincular cada edición ESA CAVES con la cavidad y sus tramos de práctica de cartografía. |
| 44. Cuevas de Eslovenia | Sistemas kársticos y cavernarios. Grupos/programas: ESA CAVES y programas de entrenamiento subterráneo en distintas ediciones. | Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Identificar la cavidad y su desarrollo topográfico, junto con las condiciones de la campaña. |
| 45. Cuevas de España | Sistemas cavernarios seleccionados para entrenamiento. Grupos/programas: ESA CAVES y equipos de formación de astronautas. | Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Confirmar cavidad, año de campaña y posible relación con la ficha de Cantabria. |
| 46. Cuevas de Cantabria, España | Instalación/cueva de Astroland. Grupos/programas: Astroland; equipos de investigación, formación y simulación de vida en entornos confinados. | Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Distinguir las áreas de la instalación Astroland y su relación con la cavidad natural. |
| 47. Piła, Polonia | LunAres Research Station, hangar aislado. Grupos/programas: LunAres; equipos internacionales y universitarios; misiones lunares y marcianas simuladas. | Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Añadir plano y superficie útil del hangar LunAres, con condiciones de iluminación y retraso de comunicaciones. |
| 48. Rzepiennik Strzyżewski, Polonia | Instalaciones de Analog Astronaut Training Center (AATC). Grupos/programas: AATC y equipos participantes en entrenamientos y simulaciones análogas. | Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Identificar la instalación del AATC y el protocolo utilizado para la actividad elegida. |
| 49. Biosphere 2, Oracle, Arizona, Estados Unidos | Ecosistema cerrado experimental y Space Analog for the Moon and Mars (SAM). Grupos/programas: Universidad de Arizona; equipos SAM; investigadores de sistemas cerrados y habitabilidad. | Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Distinguir el perímetro y los experimentos de SAM dentro de Biosphere 2. Registrar atmósfera y control ambiental. |
| 50. Colonia / instalaciones DLR, Alemania | Campañas de pruebas de trajes y tecnología Aouda. Grupos/programas: Austrian Space Forum y Deutsches Zentrum für Luft- und Raumfahrt (DLR). | Cruzar con LUNA · Colonia e identificar el recinto preciso de cada ensayo. Entrada, tramo y geometría de la cavidad o instalación. Documentar accesos, humedad y comunicaciones según la tarea. Confirmar qué recinto DLR alojó Aouda y qué configuración de traje, superficie y recorrido se usó. |

### Hábitats, instalaciones cerradas y simulaciones de aislamiento (11)

| Entrada | Campaña o uso descrito | Datos que faltan para compararla |
| --- | --- | --- |
| 51. Johnson Space Center, Houston, Texas, Estados Unidos | HERA (Human Exploration Research Analog). Grupos/programas: NASA Human Research Program; equipos de investigación de factores humanos y comportamiento. | Identificar el recinto y protocolo dentro de Johnson Space Center. Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Identificar el módulo HERA, su aforo y duración, y enlazar el protocolo de cada campaña. |
| 52. Johnson Space Center, Houston, Texas, Estados Unidos | CHAPEA / Mars Dune Alpha. Grupos/programas: NASA; tripulaciones CHAPEA y equipos científicos de salud, rendimiento humano y operaciones de superficie. | Identificar el recinto y protocolo dentro de Johnson Space Center. Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Documentar las zonas de Mars Dune Alpha usadas en superficie, condiciones operativas y duración. |
| 53. Moscú, Rusia | NEK / IBMP (Institute of Biomedical Problems). Grupos/programas: IBMP, Academia de Ciencias de Rusia; experimentos Mars-500 y SIRIUS. | Identificar el recinto y protocolo de Moscú. Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Separar experimentos Mars-500 y SIRIUS por recinto, periodo y protocolo. |
| 54. Moscú, Rusia | Instalaciones de aislamiento SIRIUS. Grupos/programas: IBMP, NASA, Roscosmos, ESA y otros socios internacionales según campaña. | Identificar el recinto y protocolo de Moscú. Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Relacionar cada campaña SIRIUS con su duración, tripulación, comunicaciones y régimen de aislamiento. |
| 55. Beijing, China | Yuegong-1 / Lunar Palace 1. Grupos/programas: Beihang University; equipos de investigación de sistemas ecológicos cerrados y soporte vital. | Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Documentar módulos de Yuegong-1, duración y métricas de soporte vital vinculadas a cada ensayo. |
| 56. Francia (instalaciones de ensayo) | SHEE – Self-deployable Habitat for Extreme Environments. Grupos/programas: Consorcio europeo SHEE y equipos de investigación de hábitats desplegables. | Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Registrar ejemplar y lugar de despliegue de SHEE, tiempo de instalación y condiciones exteriores. |
| 57. Alemania (instalaciones de ensayo) | MaMBA – Modular Analog Research Station. Grupos/programas: Equipos universitarios y de investigación alemanes; estudios de hábitats modulares. | Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Identificar la versión de MaMBA y qué módulos o tareas fueron efectivamente ensayados. |
| 58. Estados Unidos (instalaciones de ensayo) | NDU Habitat Demonstrator. Grupos/programas: University of North Dakota y colaboradores de investigación de hábitats espaciales. | Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Precisar ubicación y versión del demostrador NDU, configuración de módulos y pruebas documentadas. |
| 59. Estados Unidos (instalaciones de ensayo) | ILMH2 / instalaciones universitarias de hábitat. Grupos/programas: Equipos universitarios y grupos de investigación de factores humanos y hábitats. | Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Desambiguar la instalación ILMH2, identificar el operador y verificar protocolo y plano. |
| 60. Alemania | Luna i Flexhab. Grupos/programas: Equipos de investigación europeos y alemanes; pruebas de conceptos de hábitat lunar. | Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Ubicar el recinto Flexhab y precisar qué configuración y ambiente fueron ensayados. |
| 61. Estados Unidos | HESTIA – Human Exploration Spacecraft Testbed for Integration and Advancement. Grupos/programas: NASA y colaboradores de investigación; plataforma de integración y ensayos de sistemas. | Identificar recinto y protocolo. Documentar superficie útil, condiciones controladas, duración, comunicaciones y acceso. Identificar el recinto HESTIA y los subsistemas, límites operativos y periodo de cada prueba. |

### Entornos submarinos y acuáticos (5)

| Entrada | Campaña o uso descrito | Datos que faltan para compararla |
| --- | --- | --- |
| 62. Aquarius Reef Base, Florida Keys, Estados Unidos | Hábitat submarino frente a Key Largo. Grupos/programas: NASA NEEMO (NASA Extreme Environment Mission Operations); NOAA y Florida International University. | Precisar cuerpo de agua y sector. Documentar profundidad, visibilidad, condiciones del agua y acceso según el ensayo. Añadir la ubicación del hábitat Aquarius, profundidad de las EVA y visibilidad durante cada misión. |
| 63. Represa / lago Pavilion, Columbia Británica, Canadá | Pavilion Lake. Grupos/programas: NASA Pavilion Lake Research Project (PLRP), CSA y equipos internacionales; exploración científica subacuática. | Precisar cuerpo de agua y sector. Documentar profundidad, visibilidad, condiciones del agua y acceso según el ensayo. Ligar los transectos de buceo y muestras a una batimetría de Pavilion Lake. |
| 64. Represa y entornos acuáticos de Estados Unidos | NDU / proyectos de neutral buoyancy y entrenamiento EVA. Grupos/programas: University of Maryland Space Systems Laboratory, NASA y equipos universitarios. | Precisar cuerpo de agua y sector. Documentar profundidad, visibilidad, condiciones del agua y acceso según el ensayo. Identificar la instalación o represa concreta y el protocolo de flotabilidad del experimento. |
| 65. República Checa | Hydronaut DeepLab H03. Grupos/programas: Hydronaut; equipos de investigación de aislamiento, operaciones y factores humanos. | Precisar cuerpo de agua y sector. Documentar profundidad, visibilidad, condiciones del agua y acceso según el ensayo. Precisar emplazamiento de Hydronaut DeepLab, profundidad y condiciones de aislamiento del ensayo. |
| 66. Entornos submarinos y piscinas de entrenamiento de Estados Unidos | Neutral Buoyancy Laboratory y centros de entrenamiento EVA. Grupos/programas: NASA; astronautas, ingenieros y equipos de entrenamiento. Se incluyen como análogos operacionales de EVA, no como análogos geológicos planetarios. | Precisar cuerpo de agua y sector. Documentar profundidad, visibilidad, condiciones del agua y acceso según el ensayo. Identificar piscina y réplica usada, profundidad de trabajo, duración y configuración de la flotabilidad. |
