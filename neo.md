# neo

## Estado del arte | Calidad de un análogo lunar o marciano

### ¿Existen métricas o puntajes de similitud publicados?

- **Puntaje aplicado a un sitio completo.** Un estudio de 2026 evaluó Isla Decepción y dos de sus bases mediante diez dimensiones que incluyen geología, ambiente, logística y factores humanos. Es un precedente para estructurar una evaluación por dimensiones, con resultados propios del marco y de la campaña estudiada. [Acta Astronautica, 2026](https://doi.org/10.1016/j.actaastro.2026.05.065)
- **Sí, por propiedad.** Un preprint comparó cuatro tipos de relieve de Marte con Qaidam usando distancia euclidiana entre rasgos de imágenes. **SWIM** aporta una métrica de evidencia: usa un índice de −1 a +1 para expresar si las señales orbitales son compatibles con hielo enterrado en Marte. Su alcance es la evidencia de hielo dentro de Marte. La revisión no identificó un puntaje universal validado para sitios completos. [Qaidam, preprint de 2025](https://arxiv.org/abs/2501.08584) · [SWIM, Nature Astronomy](https://doi.org/10.1038/s41550-020-01290-z)
- **Estándares con uso documentado.** Un estudio de congreso adaptó la figura de mérito de **ISO 10788** para comparar la composición de rocas terrestres y marcianas. Un ensayo de laboratorio aplicó **NASA-STD-1008** al preparar simulantes lunares y midió la cobertura de polvo en superficies. [ISO 10788](https://www.iso.org/standard/57532.html) · [Comparación de rocas](https://indico.fais.uj.edu.pl/event/84/contributions/514/) · [NASA-STD-1008](https://standards.nasa.gov/standard/nasa/nasa-std-1008) · [Ensayo de polvo](https://doi.org/10.1007/s12567-025-00618-7)

### ¿Cómo se adapta la evaluación al objetivo de la misión?

- **Definir tarea, región, propiedad indispensable y escala.** Para perforación con Arcadia–Amazonis como referencia, interesan la profundidad del hielo y las propiedades del suelo. Para muestreo en una región como Oxia o Jezero, importan la mineralogía, el contexto geológico y lo que puede detectar el instrumento. En **JETT5**, NASA usó terreno volcánico para ensayar caminatas lunares, geología de campo y coordinación remota. [Matriz propuesta por Matías](https://github.com/MartinWilckens/Coiponautas/blob/main/Estado%20del%20arte/Investigacion_Marte_requisitos_para_analogos.md) · [NASA, JETT5](https://science.nasa.gov/missions/artemis/behind-the-scenes-of-a-nasa-moonwalk-in-the-arizona-desert/)

### ¿Se usan datos satelitales o trabajo de campo?

- **Ambos.** Los datos orbitales permiten seleccionar zonas y comparar relieve a escalas compatibles. El dron y el muestreo ayudan a comprobar rasgos locales y propiedades del suelo. En el **Salar de Pajonales**, un estudio combinó imágenes orbitales y de dron con muestras de terreno para estimar dónde buscar biofirmas. [Warren-Rhodes et al., 2023](https://doi.org/10.1038/s41550-022-01882-x)
- **Recursos del desafío Space Apps.** **Earthdata Search** y **Copernicus** (ESA) permiten encontrar elevación e imágenes terrestres. **PDS** da acceso a la topografía marciana de MOLA, y el archivo **LRO** da acceso a la topografía lunar de LOLA. Los estudios, estándares e informes citados arriba son fuentes complementarias. [Listado del desafío reproducido por HackAthlone](https://hackathlone.com/challenges/permanent-moon-base-locations-and-mars) · [Earthdata Search](https://search.earthdata.nasa.gov/) · [Copernicus](https://dataspace.copernicus.eu/) · [PDS/MOLA](https://pds-geosciences.wustl.edu/missions/mgs/mola.html) · [LRO/LOLA](https://pds-geosciences.wustl.edu/missions/lro/lola.htm)

## Brechas de los análogos y aplicación al mapa

### ¿Qué condiciones de Luna y Marte no cubre ningún análogo conocido?

- Un terreno terrestre natural reproduce condiciones parciales. En la **Luna**, quedan fuera la gravedad lunar, el vacío y el ambiente de radiación. En el polo sur, el relieve puede estudiarse en campo y la luz rasante puede ensayarse en instalaciones como LUNA. La duración de la sombra y el frío de un cráter requieren datos del emplazamiento y ensayos controlados. [Investigación lunar de Figue](figue.md) · [LRO/Diviner, recurso del desafío](https://pds-geosciences.wustl.edu/missions/lro/diviner.htm) · [Instalación LUNA](https://www.dlr.de/en/research-and-transfer/featured-topics/mission-moon/the-luna-moon-facility)
- En **Marte**, quedan fuera la gravedad marciana, la atmósfera tenue de CO₂ y el ambiente de radiación. Un lugar con hielo bajo suelo sirve para estudiar detección o perforación en determinados materiales. El desempeño con presión, polvo y gravedad marcianos requiere ensayos complementarios. [Investigación marciana de Matías](matydrox.md) · [Instalaciones de simulación de NASA](https://www.nasa.gov/reference/jsc-analogs-mockups/)

### ¿Qué tipos de lugar conviene investigar más?

- El USGS encontró una preferencia por volver a sitios familiares y recomendó ampliar el estudio de procesos sedimentarios marcianos, entre ellos los fluviales, lacustres, deltaicos, eólicos y glaciares. Esto orienta la búsqueda. Para llamar «poco estudiado» a un sitio, registrar las campañas publicadas para **ese ensayo**, el área y la fecha de búsqueda. [USGS, 2024](https://pubs.usgs.gov/publication/ofr20241042)
- **Movilidad:** campos volcánicos donde se puedan evaluar pendientes, rugosidad y obstáculos a escala del vehículo. [NASA, JETT5](https://science.nasa.gov/missions/artemis/behind-the-scenes-of-a-nasa-moonwalk-in-the-arizona-desert/)
- **Muestreo geológico:** depósitos lacustres y salares donde se puedan comparar minerales, sedimentos y su contexto. Aguas Calientes Sur tiene observaciones de campo y radar para explorar cambios en las costras. [Investigación de Matías](matydrox.md) · [Estudio de Aguas Calientes Sur](https://doi.org/10.3390/rs12060941)
- **Operaciones con baja visibilidad:** terrenos con sombras marcadas para ensayar navegación e iluminación. La comparación depende del relieve y de cuándo aparece la sombra. [Investigación de Figue](figue.md)
- **Detección de recursos:** zonas periglaciales donde se pueda evaluar la evidencia de hielo bajo el suelo. El Ternero y El Jote ofrecen un contraste documentado para este tipo de ensayo. [Estudio de campo, 2022](https://tc.copernicus.org/articles/16/1579/2022/)

### ¿Qué limitaciones prácticas tienen los análogos actuales?

- **Acceso y costo.** Registrar ruta y tiempo de traslado, transporte de equipos, infraestructura, comunicaciones y opciones de evacuación. Dejar el costo por verificar cuando falte una estimación de campaña. AMADEE-20 muestra cómo incorporar riesgos técnicos y médicos en un ensayo remoto. [Safe Mars Analog Missions](https://doi.org/10.1016/j.actaastro.2022.12.015)
- **Permisos y temporada.** Registrar acceso y autorización por actividad, como observación, dron, muestreo o perforación, junto con la ventana de operación. Estero Derecho es un santuario y el expediente de protección que incluye Aguas Calientes Sur figuraba en elaboración al consultarlo. La estacionalidad también cambia lo que se puede medir, como la humedad y rugosidad de las costras. [Ficha de Estero Derecho](https://simbio.mma.gob.cl/CbaAP/Details/1076) · [Expediente del MMA](https://expedientes.mma.gob.cl/ficha/expediente/50/parque-nacional-laguna-tuyajto-salar-de-aguas-calientes-sur-3-o-purisunchi-talar-salar-de-capur-o-talar-y-salar-el-laco-region-de-antofagasta) · [Estudio estacional](https://doi.org/10.3390/rs12060941)

### Qué mostrar en el prototipo

- **Filtro por ensayo.** Ofrecer movilidad, muestreo geológico, operaciones con baja visibilidad y detección de recursos. Cada zona se vincula con el ensayo que su evidencia permite estudiar.
- **Ficha por zona.** Mostrar qué se quiere ensayar, qué propiedad respalda la comparación, método y escala, fuente, historial de campañas y verificación pendiente. Etiquetar cada dato como medición de campo, estimación remota o hipótesis.
- **Capas y viabilidad.** Usar Copernicus y Earthdata para el contexto terrestre y PDS/LRO para referencias planetarias. Mostrar acceso, transporte, costo, permisos por actividad, temporada, comunicaciones y evacuación. Para zonas cuyo historial quede pendiente, usar «candidata, historial de campañas por verificar». [Recursos del desafío reproducidos por HackAthlone](https://hackathlone.com/challenges/permanent-moon-base-locations-and-mars)

## Resultados de las campañas análogas

- **TRIDENT.** Diseñado para llevar muestras del subsuelo lunar a la superficie y buscar volátiles. Probó suelo suelto en Atacama, ocho pozos en Haughton y seis en Bishop Tuff. En Bishop, retirar los residuos cada 2 cm en vez de 10 cm permitió seguir sin atascarse en un pozo. En la Luna, PRIME-1 quedó de lado. El taladro se desplegó y se comprobaron sus mecanismos, pero la broca no alcanzó el suelo. [Ensayos en Tierra](https://ntrs.nasa.gov/citations/20240000585) · [Resultados en vuelo](https://doi.org/10.3847/PSJ/ae0b51).
- **ERNEST.** En California recorrió 26 km en 37 horas de conducción repartidas en siete días. El reporte da el total de la campaña, sin separar desempeño por iluminación. [JPL](https://www.jpl.nasa.gov/news/nasa-testing-advanced-capabilities-for-moon-mars-rovers/).
- **CanMars.** Guardó ocho muestras en dos campañas en Utah. Se priorizaron limolitas. El laboratorio encontró los valores más altos de carbono orgánico en areniscas, aun por debajo de 0,03 % en masa. [Resultados de CanMars](https://doi.org/10.1016/j.pss.2019.04.004).

## Luna: condiciones de exploración y requisitos para análogos terrestres

**Coiponautas · NASA Space Apps Challenge 2026 · 14 de noviembre de 2026**

Esta investigación amplía las condiciones lunares reunidas en [figue.md](figue.md) y aplica la secuencia de [matydrox.md](matydrox.md): región → tarea → evidencia → ensayo terrestre. El desafío oficial pide **identificar y caracterizar análogos terrestres nuevos con datos abiertos de la Tierra, la Luna y Marte**, y presentar los resultados en un mapa u otra herramienta. La pregunta de Coiponautas es qué sitio terrestre cubriría una necesidad concreta de misión, qué aportaría frente a un sitio conocido y qué falta medir antes de elegirlo. [Desafío oficial de NASA Space Apps](https://www.spaceappschallenge.org/2026/challenges/permanent-moon-base-locations-and-mars/)

### 1. Cuatro regiones de referencia

Tres regiones polares cubren decisiones distintas de operación de una base: **moverse con baja visibilidad, prospectar volátiles y sostener energía y comunicaciones**. Mare Tranquillitatis agrega exploración de cavidades en un terreno volcánico de baja latitud. Haber elegido cuatro perfiles permite comparar tareas al mismo nivel que Arcadia–Amazonis, Jezero, Gale y Oxia Planum, sin duplicar fichas que responden a la misma pregunta.

| Región lunar | Tarea que orienta la búsqueda terrestre | Qué medir en el análogo |
| --- | --- | --- |
| **de Gerlache Rim 2**, con Connecting Ridge y Shackleton como referencias cercanas | Navegación de rover o EVA con Sol rasante y transiciones de sombra | Pendiente longitudinal/transversal, obstáculos a escala del rover, contraste, errores de detección y paradas |
| **Haworth** | Entrar a un sector oscuro, detectar hielo y recuperar una muestra con condiciones controladas | Métricas de detección frente a controles, profundidad y propiedades del medio, recuperación y cambio de temperatura de la muestra |
| **Macizo Malapert** | Escoger un nodo elevado que mantenga el enlace de un equipo móvil y soporte su operación energética | Visibilidad del enlace a lo largo de la ruta, interrupción máxima, recuperación y consumo durante cortes |
| **Pozo de Mare Tranquillitatis** | Cartografiar y mantener enlace con un robot al pasar del exterior a una cavidad | Cobertura de mapa, error de localización, continuidad de telemetría, posición de repetidores y retorno seguro |

**Estado Artemis, al 14 de noviembre de 2026.** NASA prevé Artemis III en órbita baja terrestre en 2027 y el aterrizaje tripulado cerca del polo sur con Artemis IV, previsto para comienzos de 2028. Las tres regiones polares de la tabla figuran entre las nueve áreas de aterrizaje presentadas por NASA. Connecting Ridge y Shackleton se usan aquí como referencias de iluminación y topografía. La ubicación específica de una base requiere decisiones adicionales de emplazamiento. [NASA, Artemis III](https://www.nasa.gov/missions/artemis/nasas-artemis-iii-mission-to-test-future-moon-lander-operations/) · [NASA, Artemis IV](https://www.nasa.gov/mission/artemis-iv/) · [NASA NTRS, selección de nueve regiones](https://ntrs.nasa.gov/citations/20250011660)

**El estudio de los 130 puntos mencionado en el audio.** Wueller et al. (2026) compararon 130 puntos representativos de aterrizaje usando topografía, iluminación y acceso modelado a zonas de sombra permanente. Su tabla 1 distingue **7** puntos en de Gerlache Rim 2, **11** en Haworth y **5** en Malapert. El apéndice A1 permite ubicar cada punto y A2 da ventanas simuladas de visibilidad al Sol y a la Tierra para los veranos australes de 2025–2032. Estos datos permiten cruzar condiciones en el mismo lugar. Cuando la cobertura o la escala cambian, registrar el dato regional como contexto y dejar la medición local pendiente. En el piloto prioricé visibilidad y obstáculos. Para Haworth, la temperatura sí es decisiva para la estabilidad de volátiles; para abrasión, se requiere una ficha de polvo por material y ensayo. [Wueller et al., 2026, tablas 1, A1 y A2](https://doi.org/10.1029/2025JE009434) · [Datos abiertos del estudio](https://doi.org/10.5281/zenodo.17084058)

### 2. de Gerlache Rim 2 — movilidad con Sol rasante

- **Relieve y luz.** El objetivo es un tramo de borde a aproximadamente **88,2° S**, con obstáculos, desniveles y sombras que cambian con el azimut solar. NASA publica un modelo local LOLA de **5 m/píxel** para el sector SL2. La cresta Connecting Ridge se estudia aparte: Gläser et al. estimaron hasta **88 % de iluminación media** para un punto de la cresta a **2 m de altura** en una simulación de 2017–2037 con intervalos de una hora. Para una ruta, interesa cuánto dura cada tramo de sombra, dónde corta el corredor y qué queda visible desde la altura de la cámara. El porcentaje pertenece a ese punto de la cresta. [NASA, topografía LOLA](https://pgda.gsfc.nasa.gov/products/78) · [Gläser et al., 2018](https://doi.org/10.1016/j.pss.2017.07.006) · [NASA, visualización y entorno polar](https://www.nasa.gov/reference/moonbase-environment/)
- **Ejemplo de ventana local.** En el punto **dGR2_K2023** (88,450° S, 67,859° O), Wueller et al. modelaron hasta **8 días consecutivos** con visibilidad simultánea al Sol y a la Tierra en el verano austral de 2026, y **20 días** en la ventana de 2027. El cambio corresponde a un mismo punto bajo dos ventanas del modelo. Para estimar sombras sobre un recorrido se requiere la geometría de cada tramo. [Wueller et al., 2026, tablas A1 y A2](https://doi.org/10.1029/2025JE009434)
- **Temperatura y superficie.** Williams et al. describieron una temperatura superficial de alrededor de **200 K (−73 °C)** durante partes del verano para el punto C2 de Connecting Ridge, con descensos al pasar sombras. C2 y SL2 son áreas distintas. La topografía regional permite elegir un corredor, mientras que los bloques, el regolito suelto y la pendiente a escala de rueda requieren datos más finos para evaluar movilidad. Medir granulometría, densidad y resistencia al corte solo si se van a comparar tracción o excavación. [Williams et al., 2019, figura 10d](https://doi.org/10.1029/2019JE006028) · [NASA, Lunar Surface Data Book](https://ntrs.nasa.gov/citations/20230007818)
- **Pregunta de ensayo.** ¿En qué tramos una cámara pierde el borde de un obstáculo cuando cambia la posición del Sol? Comparar el mismo recorrido con iluminación de referencia y rasante. Registrar obstáculos detectados y omitidos frente a un levantamiento independiente, error de posición, interrupciones y tiempo de recuperación. La luz difusa del cielo terrestre cambia el contraste medido; una instalación como LUNA permite repetir el ensayo con iluminación dirigida. JPL ya ensayó el rover ERNEST con sombras largas de amanecer y atardecer en California. [NASA/JPL, ERNEST](https://www.jpl.nasa.gov/news/nasa-testing-advanced-capabilities-for-moon-mars-rovers/) · [DLR, instalación LUNA](https://www.dlr.de/en/research-and-transfer/featured-topics/mission-moon/the-luna-moon-facility)

### 3. Haworth — acceso a sombra permanente y prospección de hielo

- **Microambientes distintos.** La región candidata y el fondo frío son unidades diferentes para la planificación. En el fondo de Haworth, Diviner sustenta valores aproximados de **20–30 K en invierno y 30–45 K en verano** para la zona fría descrita por Williams et al. En la región de aterrizaje, Wueller et al. identificaron desde **HW10** acceso modelado a sombra permanente con máximas por debajo de **110 K** bajo su criterio de recorrido. Distancia, obstáculos, tiempo de ida y vuelta y enlace deben evaluarse sobre una ruta concreta. [Williams et al., 2019](https://doi.org/10.1029/2019JE006028) · [Wueller et al., 2026](https://doi.org/10.1029/2025JE009434) · [NASA PGDA, modelos topográficos de Haworth](https://pgda.gsfc.nasa.gov/products/78)
- **Hielo y fuerza de la evidencia.** M³ de Chandrayaan-1 encontró firmas espectrales compatibles con hielo expuesto cerca de Haworth, en píxeles de unos **280 × 280 m** por el estudio de Li et al. El espectro sondea la superficie óptica, de profundidad inferior a unos milímetros. La temperatura máxima anual sirve para evaluar estabilidad potencial; la extensión, ley y profundidad de un depósito excavable siguen abiertas. **Cabeus** es una referencia independiente: LCROSS detectó agua al observar la pluma de impacto y estimó **5,6 ± 2,9 % de hielo en masa** en el regolito del punto impactado a partir de la masa eyectada observable. Esa cifra corresponde a Cabeus. [Li et al., 2018](https://doi.org/10.1073/pnas.1802345115) · [Colaprete et al., 2010](https://doi.org/10.1126/science.1186986)
- **Pregunta de ensayo.** ¿Puede el equipo detectar un objetivo con hielo y recuperar una muestra con mínima alteración durante una incursión oscura? El campo puede probar gestión de luz, navegación, enlace y manipulación. En instalación, usar objetivos ciegos con profundidad y contenido de hielo documentados y blancos secos. Medir falsos positivos, recuperación, energía de perforación y cambio térmico. DLR/ESA ya hicieron un ensayo controlado de detección simulada de hielo en LUNA. Las condiciones criogénicas en vacío requieren ensayos específicos. [DLR, Polar Explorer](https://www.dlr.de/en/latest/news/2025/water-ice-on-the-moon-simulated-detection-in-the-luna-facility)

### 4. Macizo Malapert — enlace y energía desde terreno elevado

- **Terreno y visibilidad.** El macizo es una referencia cerca de **86° S**. Un estudio de rutas geológicas usa un punto de aterrizaje **hipotético** a **85,964° S y 357,681° E** cercano a la cumbre. La elevación local favorece la visibilidad hacia la Tierra, que depende de la posición, altura de antena y horizonte. Laderas y cráteres cercanos pueden ocultar un rover a un repetidor, aunque el repetidor vea la Tierra. NASA publica topografía y pendientes para Site23. [Estudio de rutas geológicas en Malapert](https://doi.org/10.1029/2024JE008905) · [NASA, contexto de Malapert](https://science.nasa.gov/image-detail/20100618/) · [NASA PGDA, Site23](https://pgda.gsfc.nasa.gov/products/78)
- **Energía y accesibilidad.** Para comparar nodos, calcular en la misma geometría de terreno la visibilidad al Sol y al otro extremo del enlace, con altura y ventana definidas. Importan la máxima sombra continua, el plazo para recuperar el enlace y los tramos transitables desde el nodo. Convertir exposición solar a energía requiere orientación, potencia, almacenamiento y carga. Tierra permite medir el resultado operativo de apagar la alimentación o perder comunicaciones en un itinerario trazado. [NASA PGDA, iluminación polar y visibilidad de la Tierra](https://pgda.gsfc.nasa.gov/products/69) · [NASA, entorno de Moon Base](https://www.nasa.gov/reference/moonbase-environment/)
- **Pregunta de ensayo.** ¿Dónde situar un repetidor para completar una ruta entre cumbre, ladera y depresión? Comparar una pasada sin repetidor y otra con repetidor de altura definida. Registrar pérdida de paquetes por tramo, máxima caída consecutiva y porcentaje de recorrido con telemetría. Usar la misma frecuencia, antena, trayecto y protocolo en cada pasada. Los efectos de atmósfera, obstáculos y tipo de suelo condicionan la transferencia del resultado a la Luna.

### 5. Pozo de Mare Tranquillitatis — acceso y cartografía de cavidades

- **Geología y geometría.** El pozo está en lavas basálticas de la cara visible a **8,3355° N, 33,222° E**. Las imágenes oblicuas de LROC muestran paredes abruptas y bloques en el fondo. NASA estimó una profundidad del orden de **100 m** a partir de sombras. El radar Mini-RF y los modelos de dispersión sustentan la existencia probable de un conducto bajo el borde occidental. Su extensión completa, estabilidad y accesibilidad para una misión siguen por comprobar. [NASA, imágenes del pozo](https://science.nasa.gov/photojournal/new-views-of-lunar-pits/) · [Carrer et al., 2024](https://doi.org/10.1038/s41550-024-02302-y) · [Wagner y Robinson, nubes de puntos abiertas](https://doi.org/10.5281/zenodo.6622042)
- **Temperatura y refugio.** Horvath et al. estimaron cerca de **290 K (17 °C)** en el interior siempre sombreado de una cavidad modelada, a partir de datos Diviner y simulación térmica. Esa estimación motiva estudiar el subsuelo como refugio térmico. Aplicarla a un diseño requiere comprobar la temperatura real, la geometría y el acceso. [Horvath et al., 2022](https://doi.org/10.1029/2022GL099710)
- **Pregunta de ensayo.** ¿Puede un robot construir un mapa y volver a la entrada con visibilidad baja y sin posicionamiento externo? Usar un tramo terrestre con recodos, medir la fracción cartografiada, la deriva de posición, la telemetría y la posibilidad de retorno con enlace directo o repetidor. Para simular el descenso vertical hace falta un tramo o instalación cuya geometría permita ensayarlo. **Cueva de los Verdes, Lanzarote**, es el comparador conocido: PANGAEA-X ya probó navegación y mapeo robotizado dentro de su tubo. [ESA, ensayo del rover en PANGAEA-X](https://www.esa.int/ESA_Multimedia/Images/2018/08/Astronaut_and_rover_in_lava_tube)

### 6. Aplicación al mapa web — piloto lunar en Pali-Aike

**Selección del caso.** Escogí movilidad con luz rasante para la primera ficha porque tiene un comparador de campo de la misma tarea, un caso polar respaldado por LRO y una propiedad que puede cambiar si el usuario modifica la duración del ensayo. La hipótesis terrestre es el **cono de Pali-Aike, Magallanes**, en torno a **52,11222° S, 69,70750° O**, con foco en **aproximaciones de menor pendiente**. Sernageomin describe un cráter de **160–180 m** de ancho, paredes de **40–45°** y pendientes de **10–22°** hacia la base. Las paredes ayudan a plantear escenarios de sombra. La ruta debería escogerse con el límite longitudinal y transversal del rover, midiendo por separado las transiciones y los obstáculos. El área tiene valor geológico y patrimonial y está gestionada por CONAF. [Sernageomin, ficha Cono de Pali-Aike](https://geositiosdechile.sernageomin.cl/wp-content/uploads/sites/4/2024/05/Libro%20Geositios%20de%20Chile%202024.pdf) · [CONAF, Parque Nacional Pali Aike](https://www.conaf.cl/parque_nacionales/parque-nacional-pali-aike/)

**Comprobación con elevación abierta.** Extraje una ventana de **17 × 17 celdas** alrededor de la coordenada de la ficha, de unos **485 × 525 m**. El modelo superficial Copernicus GLO-30 da **185,8–250,1 m** dentro de esa ventana. Para reproducirla en el GeoTIFF original, seleccionar filas **395–411** y columnas **694–710** incluidas, con índices desde cero. A esta latitud, la celda mide unos **28,5 × 30,9 m** y el ancho publicado del cráter ocupa del orden de **5–6 celdas**. Esto permite ubicar el relieve a escala de mapa. Los bloques, el perfil a escala del rover y una ruta apta requieren mayor resolución. [Baldosa Copernicus GLO-30 consultada](https://copernicus-dem-30m.s3.amazonaws.com/Copernicus_DSM_COG_10_S53_00_W070_00_DEM/Copernicus_DSM_COG_10_S53_00_W070_00_DEM.tif) · [Ficha del producto Copernicus](https://dataspace.copernicus.eu/explore-data/data-collections/copernicus-contributing-missions/collections-description/COP-DEM)

**Cribado reproducible de duración.** Para esa latitud y horizonte ideal plano, el centro del Sol tarda aproximadamente **33 min en equinoccio**, **41 min en el solsticio de verano austral** y **46 min en el de invierno austral** en ascender de 0° a 5° de elevación. Los tiempos son por ventana, con un intervalo simétrico al atardecer en el modelo. El límite de 5° es un supuesto para probar la herramienta; el perfil real se deriva del sitio lunar y del ensayo. Relieve, nubosidad, refracción y horario de acceso pueden recortar o cambiar la ventana observable. Para repetir este cálculo, usar `H(h) = acos((sin(h) − sin(φ) sin(δ)) / (cos(φ) cos(δ)))` en grados y `4 × [H(0°) − H(5°)]` en minutos, con latitud `φ = −52,11222°` y declinación `δ = 0°, −23,44°, +23,44°`. [NASA, geometría solar del entorno polar lunar](https://www.nasa.gov/reference/moonbase-environment/)

| Si el usuario pide… | Resultado que mostraría la ficha |
| --- | --- |
| Una pasada de 20 min con el Sol entre 0° y 5° | Pali-Aike pasa el cribado de duración ideal en los tres escenarios. Quedan por confirmar horizonte, dirección del Sol respecto del tramo, obstáculos, clima y acceso con CONAF. |
| 60 min continuos con el Sol natural entre 0° y 5°, en uno de los tres escenarios calculados | Pali-Aike queda fuera por duración en la configuración modelada. Para una prueba larga con ángulo fijo se puede comparar una instalación con fuente controlada y programar otro ensayo de integración en campo. |
| Obstáculos de 25 cm como criterio obligatorio de una pasada | **Pendiente.** Un DEM terrestre de decenas de metros sirve para ubicar el cono y trazar aproximaciones, pero la altura y la posición de los obstáculos se verifican con fotogrametría o levantamiento local. |

**Comparador y prueba de valor.** Usar la campaña de ERNEST en el desierto de Colorado, California, como precedente de campo. Comparar recorridos con categorías equivalentes de pendiente y luz, usando la misma cámara, velocidad y método de validación. La ventaja que se buscaría en Pali-Aike es **más transiciones útiles de luz a sombra por cada 100 m de recorrido transitable** para un ensayo corto. Contar una transición solo si cumple el rango angular y de contraste del ensayo y ocurre en un tramo aceptado por el rover. Medir aparte cuántos obstáculos omite el sistema de detección y cuánto tarda en recuperarse. LUNA permite repetir a ángulo y contraste controlados. La comparación de desempeño, costos y acceso sigue pendiente. La búsqueda inicial tampoco establece cuántas campañas de esta tarea se han hecho allí. [NASA/JPL, campaña de ERNEST](https://www.jpl.nasa.gov/news/nasa-testing-advanced-capabilities-for-moon-mars-rovers/) · [DLR, LUNA](https://www.dlr.de/en/research-and-transfer/featured-topics/mission-moon/the-luna-moon-facility)

### 7. Datos, límites y ficha común con Marte

| Variable | Producto o método | Límite clave |
| --- | --- | --- |
| Relieve y sombra | LRO/LOLA y LROC para la referencia. Copernicus DEM GLO-30, NASADEM y Sentinel-2 donde haya cobertura terrestre, seguidos de levantamiento fino. | Comparar escalas y resolución efectiva. Un píxel de 5 m puede ser interpolado y uno de decenas de metros en Tierra puede suavizar un obstáculo decisivo. |
| Temperatura y volátiles | Diviner, M³, LCROSS y datos de campaña terrestre | Separar temperatura superficial, estabilidad inferida, detección espectral y medición de muestra. Registrar profundidad, hora, estación y resolución. |
| Regolito y polvo | Medir tamaño y forma de partículas, densidad, tracción y cohesión según la tarea. Ensayar abrasión, adhesión y sellado con simulante y protocolo de hardware. | El polvo terrestre responde a humedad, atmósfera y meteorización. La carga electrostática lunar y la abrasión necesitan condiciones y materiales definidos. |
| Vacío, gravedad, radiación y micrometeoritos | Instalaciones, simulaciones y protocolos de ingeniería según la variable | El ensayo natural caracteriza la operación terrestre. La gravedad lunar es cerca de un sexto de la terrestre; los mecanismos de transferencia térmica, la radiación ionizante y el flujo de impactos requieren modelos o ensayos específicos. |

[NASA PDS, LRO](https://pds-geosciences.wustl.edu/missions/lro/) · [ESA, ficha Copernicus DEM](https://dataspace.copernicus.eu/explore-data/data-collections/copernicus-contributing-missions/collections-description/COP-DEM) · [NASA Earthdata Search](https://search.earthdata.nasa.gov/) · [NASA-STD-1008, ensayos de polvo](https://standards.nasa.gov/standard/nasa/nasa-std-1008) · [NASA, entorno del polo sur lunar](https://www.nasa.gov/reference/moonbase-environment/)

**Ficha del prototipo.** Guardar tarea, región planetaria, polígono o tramo terrestre, criterio con unidad y umbral, dato y resolución, método, comparador, y resultado **cumple / descarta / pendiente** por criterio. La logística y los permisos también pueden determinar si la campaña es viable. La web puede cambiar la recomendación ante un requisito nuevo y mostrar la evidencia responsable del cambio. La misma ficha sirve para la duración de luz en Pali-Aike y la verificación de hielo bajo cobertura planteada por Matías para Arcadia–Amazonis. [Criterios y antecedentes](#estado-del-arte--calidad-de-un-análogo-lunar-o-marciano) · [Prospección terrestre en matydrox.md](matydrox.md#prospección-mundial-de-sitios-terrestres-para-analogías-marcianas)

**Alcance del piloto.** Las cifras lunares vienen de estudios y productos publicados. El trabajo nuevo es la extracción local de elevaciones y el cribado geométrico de la ventana solar en Pali-Aike. Faltan el perfil de horizonte del corredor, la validación de obstáculos y contraste, la comparación de desempeño con el análogo de referencia y la comprobación del historial y acceso del sector.

## Rama lunar para XMind

Copia el bloque en un archivo Markdown para importarlo en XMind.

```markdown
# Luna · Referencias y ensayos para análogos terrestres

## Desafío de Coiponautas

- Encontrar y caracterizar sitios en la Tierra con datos abiertos de Tierra, Luna y Marte.
- Entrada de la web → tarea de misión, región de referencia, escala y requisitos.
- Salida en el mapa → candidato terrestre, análogo conocido, evidencia, criterio que cumple y prueba pendiente.

## ¿Por qué priorizar el polo sur?

- Artemis III → demostración en órbita terrestre. Artemis IV → alunizaje polar previsto para comienzos de 2028.
- Sol bajo y sombras largas → navegación y autonomía energética.
- Regiones en sombra permanente → prospección de volátiles y trabajo en oscuridad.
- Relieve fuerte y horizonte variable → rutas y enlaces de comunicaciones.
- Wueller et al. estudiaron 130 puntos de aterrizaje. Usar el punto y la ventana del modelo para cruzar datos. Un indicador de un sector vecino sirve de contexto.

## Polo sur · Tres referencias

### de Gerlache Rim 2 · Movilidad con baja visibilidad

- Pendientes, obstáculos y cambios entre luz y sombra. LOLA ofrece topografía del sector SL2.
- Connecting Ridge y borde de Shackleton → referencias próximas. Un punto de la cresta alcanza 88 % de iluminación media modelada a 2 m de altura, en 2017–2037.
- Ensayo terrestre → repetir un recorrido con luz rasante y de referencia. Medir obstáculos omitidos, error de posición y paradas.

### Haworth · Detección y muestreo de hielo

- El fondo frío alcanza aproximadamente 20–30 K en invierno y 30–45 K en verano según Diviner.
- M³ detectó firmas de hielo expuesto cerca de Haworth. La profundidad y concentración de un depósito excavable quedan abiertas.
- Cabeus → LCROSS estimó 5,6 ± 2,9 % de hielo en masa en el punto del impacto.
- Ensayo terrestre → navegar y manipular muestras en oscuridad. Medir detección y recuperación con blancos secos y muestras de contenido conocido en instalación.

### Macizo Malapert · Comunicaciones y energía

- Cumbre con visibilidad favorable hacia la Tierra. Cráteres y laderas pueden ocultar el rover a un repetidor.
- Evaluar duración máxima de sombra, línea de vista y enlace en la ruta.
- Ensayo terrestre → repetir el recorrido con y sin repetidor. Medir pérdida de paquetes y máxima interrupción.

## Fuera del polo · Mare Tranquillitatis

- Pozo en lavas basálticas de la cara visible, a 8,3355° N y 33,222° E.
- Imágenes muestran paredes abruptas y bloques. El radar apoya la hipótesis de un conducto bajo el borde occidental.
- Cavidad sombreada modelada cerca de 290 K. Estabilidad y acceso para una misión siguen por comprobar.
- Ensayo terrestre → explorar una cavidad con robot, medir cobertura de mapa, deriva, enlace y retorno. Control conocido → PANGAEA-X, Cueva de los Verdes, Lanzarote.

## Piloto para mostrar al jurado · Pali-Aike, Magallanes

- Candidato → aproximaciones al cono de Pali-Aike. Sernageomin cartografió un cráter de 160–180 m y pendientes de 10–22° hacia la base.
- Datos abiertos → Copernicus GLO-30 representa el cráter con unas 5–6 celdas de ancho. Para ubicar obstáculos del rover hace falta un levantamiento más fino.
- Tarea → navegación robótica con Sol rasante y sombras de relieve. Comparador de campo → ERNEST de JPL en el desierto de Colorado, California.
- Cribado → 33–46 min por ventana entre 0° y 5° en equinoccio y solsticios, con horizonte plano. Una pasada de 20 min pasa el cribado de duración. Con 60 min continuos queda fuera en esos escenarios.
- Ventaja a comprobar → más transiciones útiles de luz a sombra por cada 100 m transitables frente al comparador.
- Pendiente → horizonte, detalle de obstáculos, contraste y acceso con CONAF. Historial de campañas de la tarea por verificar.
- Valor de la web → explicar qué requisito cambia la recomendación e indicar la próxima medición. La misma ficha se puede aplicar a la verificación de hielo bajo cobertura en Arcadia–Amazonis.
```


## Bitácora de la madrugada · 15 de noviembre de 2026

- **Punto de partida (WhatsApp).** Buscar un sitio poco usado que permitiera repetir mejor una prueba real y ensayar algo pendiente. Empezamos por hielo bajo suelo y TRIDENT.
- **TRIDENT.** En Haughton se hicieron ocho pozos. El vuelo fue a la Luna, donde Athena quedó de lado y el taladro se accionó sin perforar. Esa secuencia no da una razón para repetir el mismo ensayo en otro suelo.
- **Pali-Aike.** Modelamos rutas de abastecimiento con Sol rasante. El oeste dio 30 min y el este 22 min en una fecha. Sirve para priorizar un tramo, pero queda por demostrar qué ventaja tendría frente a California. Pajonales quedó como candidato para extracción de agua de sulfatos.
- **Qué cambió.** Partir por la decisión del ensayo y exigir evidencia para comprobarla. En el atlas, Saskylakh cumple por terreno poligonal y queda pendiente al exigir profundidad de hielo. NASA POWER ayuda a buscar regiones. El CSV de 2024 tiene latitud y longitud invertidas y presión en kPa rotulada como hPa.
