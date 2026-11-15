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

## Ensayos análogos · qué se probó y dónde se rompe la comparación

En el XMind, un análogo representa una condición o tarea a una escala concreta. Las referencias planetarias de abajo relacionan cada ensayo con los sitios estudiados por el equipo.

### TRIDENT · Hielo bajo suelo, Arcadia–Amazonis

**Ensayo y resultado.** NASA Ames y Honeybee ensayaron la perforación en varios materiales terrestres. En Haughton, Canadá, hicieron ocho pozos en un terreno que incluía material congelado. En Bishop Tuff, California, retirar los recortes cada 2 cm en vez de 10 cm permitió avanzar sin atascarse en un pozo. Antes se había probado en suelo suelto en Atacama. [Resultados de campo de NASA Ames](https://ntrs.nasa.gov/citations/20240000585) · [Ensayos de Bishop Tuff](https://ntrs.nasa.gov/citations/20240000608)

**Dónde se rompe.** Estos ensayos caracterizaron la broca en materiales terrestres. Arcadia–Amazonis es la referencia del equipo para la tarea de perforar hielo bajo suelo. El vuelo de TRIDENT fue lunar. Athena quedó de lado y la broca se accionó sin alcanzar el suelo, por lo que la extracción de regolito lunar quedó sin medir. [NASA, pruebas de PRIME‑1 en la Luna](https://www.nasa.gov/missions/artemis/nasas-lunar-drill-technology-passes-tests-on-the-moon/)

### ERNEST · Movilidad con luz variable, polo sur lunar

**Ensayo y resultado.** JPL probó movilidad y autonomía en terreno rocoso del desierto de Colorado, en California, al amanecer, al atardecer y de noche. Hubo pruebas con iluminadores. Publicó 26 km y 37 horas de conducción repartidas en siete días. De Gerlache Rim 2 es nuestra referencia para relacionar la tarea con el relieve y las sombras del polo. [Campaña ERNEST de JPL](https://www.jpl.nasa.gov/news/nasa-testing-advanced-capabilities-for-moon-mars-rovers/) · [Cartografía e iluminación polar](https://doi.org/10.1029/2025JE009434)

**Dónde se rompe.** La atmósfera terrestre dispersa luz hacia las sombras. También cambian la gravedad y la interacción de las ruedas con el suelo. El reporte entrega el total de la campaña y deja sin cuantificar el desempeño por condición de luz. [NASA, entorno del polo sur lunar](https://www.nasa.gov/reference/moonbase-environment/) · [Campaña ERNEST de JPL](https://www.jpl.nasa.gov/news/nasa-testing-advanced-capabilities-for-moon-mars-rovers/)

### CanMars · Selección de muestras, Jezero

**Ensayo y resultado.** Cerca de Hanksville, Utah, un equipo remoto usó un rover para seleccionar muestras en afloramientos sedimentarios. Guardó ocho en las campañas de 2015 y 2016 y priorizó limolitas para retorno simulado. En el conjunto almacenado durante la simulación, las areniscas dieron los mayores valores de carbono orgánico total, con cifras bajo 0,03 % en masa. [Campaña CanMars](https://doi.org/10.1016/j.pss.2018.07.011) · [Selección y análisis de muestras](https://doi.org/10.1016/j.pss.2019.04.004) · [Validación de campo y laboratorio](https://www.sciencedirect.com/science/article/pii/S0032063318300655)

**Dónde se rompe.** Utah permitió comprobar las decisiones del equipo contra análisis de laboratorio. La preservación de orgánicos depende de la historia geológica local. El resultado de esas muestras describe los sedimentos de Utah, mientras que la preservación en Jezero requiere sus propias observaciones. [Validación de campo y laboratorio](https://www.sciencedirect.com/science/article/pii/S0032063318300655)

### Polar Explorer · Detección de hielo, Haworth

**Ensayo y resultado.** En la instalación LUNA de Colonia, DLR enterró blancos de acrílico en simulante de regolito para representar el contraste dieléctrico del hielo con el suelo. La campaña usó radar de subsuelo y sísmica para localizar los blancos. El radar del rover y las imágenes de superficie permitieron construir una representación 3D. [DLR, campaña Polar Explorer](https://www.dlr.de/en/latest/news/2025/water-ice-on-the-moon-simulated-detection-in-the-luna-facility)

**Dónde se rompe.** Los blancos tenían geometría conocida y simulaban el contraste instrumental. El acrílico deja fuera la distribución de hielo real mezclado con regolito y el frío de la sombra permanente de Haworth. [DLR, montaje](https://www.dlr.de/en/latest/news/2025/water-ice-on-the-moon-simulated-detection-in-the-luna-facility) · [Volátiles en Haworth](https://doi.org/10.3847/psj/abf3c5)

### PANGAEA-X · Cartografía de túneles, Mare Tranquillitatis

**Ensayo y resultado.** Durante la campaña de ESA en 2017, un equipo cartografió a pie parte de la Cueva de los Verdes, en Lanzarote, con un escáner portátil y otro fijo. Ambos produjeron un modelo 3D de un tramo de 1,3 km en menos de tres horas, desde el interior y sin señal de posicionamiento satelital. [ESA, cartografía 3D de la campaña](https://blogs.esa.int/caves/2018/03/13/the-bowels-of-earth-in-3d/)

**Dónde se rompe.** El recorrido se hizo en una galería transitable a pie. El descenso por el pozo, el acceso desde el borde y el funcionamiento en vacío quedaron fuera de ese ensayo. La geometría del conducto lunar se infiere de radar orbital. [ESA, ensayo terrestre](https://blogs.esa.int/caves/2018/03/13/the-bowels-of-earth-in-3d/) · [Radar del pozo lunar](https://doi.org/10.1038/s41550-024-02302-y)

### ExoFiT · Operación remota y análisis de muestras, Oxia Planum

**Ensayo y resultado.** En Atacama, en 2019, se operó el rover de prueba Charlie desde el Reino Unido. La campaña ensayó la secuencia que va de la selección de un punto al muestreo. Con prototipos representativos del espectrómetro Raman de Rosalind Franklin, el equipo identificó minerales y señales orgánicas en muestras terrestres. [ESA, ensayo ExoFiT](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/Exploration/ExoMars/Fit_for_Mars) · [Resultados Raman](https://doi.org/10.1038/s41598-021-81014-z)

**Dónde se rompe.** Se ensayaron el flujo de trabajo y el análisis de muestras de un desierto terrestre con instrumentos representativos. La preservación de compuestos orgánicos de Oxia Planum y la operación de los instrumentos bajo presión y radiación marcianas quedan fuera de lo medido en esa campaña. [Resultados Raman](https://doi.org/10.1038/s41598-021-81014-z)

## Chajnantor · candidato para ensayar detección de hielo enterrado

**Sitio y evidencia.** El sondeo B3, en la ladera oriental del volcán Chajnantor (22°59′25″ S, 67°43′44″ O, alrededor de 5.075 m), encontró suelo volcánico alterado, de grano fino, cementado por hielo. Los autores estimaron un 46% de hielo por volumen hasta 2 m en ese sondeo y midieron un deshielo superficial máximo de 14 cm durante su estudio. B4 y B5, en el entorno del mismo volcán, quedaron clasificados sin permafrost. Haría falta comprobar al momento del ensayo si tienen hielo o agua en el intervalo que se escanee. [Sondeo B3](https://doi.org/10.1080/15230430.2021.1878739) · [Comparación de sondeos B3–B5](https://doi.org/10.1080/15230430.2025.2532202)

**Por qué sería un ensayo análogo.** Reproduce una tarea lunar específica: recorrer suelo mineral con un radar de subsuelo, interpretar sus ecos y decidir dónde tomar una muestra. En LUNA, Polar Explorer ensayó ese flujo con blancos de acrílico en simulante. En Chajnantor se podría repetir sobre hielo real en terreno natural y cotejar las predicciones con muestras del suelo. La prueba consistiría en marcar dónde se espera hielo y a qué profundidad antes de ver los resultados de los sondeos, y luego contar aciertos, falsos positivos y errores de profundidad. [Campaña Polar Explorer](https://www.dlr.de/en/latest/news/2025/water-ice-on-the-moon-simulated-detection-in-the-luna-facility) · [Montaje de LUNA](https://elib.dlr.de/220145/1/EGU25-19008-print.pdf)

**Qué queda fuera.** Diviner estimó 20–45 K (−253 a −228 °C) en el fondo en sombra de Haworth. En una consulta de NASA POWER para 2025, la mínima diaria de aire más baja estimada fue −14,1 °C en Chajnantor y −75,7 °C en Vostok. Sentinel‑2 clasificó el entorno inmediato de B3 como suelo sin vegetación el 19 de abril de 2025 y como nieve o hielo superficial el 20 de agosto. Esas capas sirven para planificar el trabajo de campo. El hielo enterrado se respalda con el sondeo y el frío de Haworth se ensayaría en una cámara. [Diviner en Haworth](https://doi.org/10.1029/2019JE006028) · [NASA POWER](https://power.larc.nasa.gov/docs/services/api/temporal/daily/) · [Sentinel‑2, abril](https://earth-search.aws.element84.com/v1/collections/sentinel-2-l2a/items/S2A_19KFQ_20250419_1_L2A) · [Sentinel‑2, agosto](https://earth-search.aws.element84.com/v1/collections/sentinel-2-l2a/items/S2B_19KFQ_20250820_0_L2A) · [Mapa chileno de permafrost](https://tc.copernicus.org/articles/20/4681/2026/)

**Antecedente comparable.** En Askja, Islandia, ya se probó radar sobre hielo enterrado y se contrastó con sondeos. En la revisión de Chajnantor encontré estudios de suelo y permafrost, pero no una campaña publicada de detección planetaria de hielo con radar en el sector B3. Quedan por confirmar el historial, el acceso y qué ventaja concreta ofrecería frente a Askja. [Ensayos de radar en Askja](https://doi.org/10.1029/2023JE007834)

**Para una base permanente.** Antes de contar con agua local, hay que saber dónde está, a qué profundidad y en qué cantidad. Un sensor que confunde una capa seca con hielo puede llevar a gastar tiempo y energía y mandar el taladro al lugar equivocado. La prospección ayuda a decidir dónde vale la pena perforar y medir. Si el depósito resulta aprovechable, el agua local podría reducir la dependencia de envíos desde la Tierra y, una vez procesada, aportar agua potable y oxígeno. El ensayo de radar cubre esa primera decisión. La recuperación, purificación y capacidad de suministro sostenido requieren pruebas propias. [Objetivo de prospección de VIPER](https://science.nasa.gov/mission/viper/) · [NASA, tecnologías de superficie para una base lunar](https://www.nasa.gov/lunar-surface-technology/)

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

### 6. Datos, límites y ficha común con Marte

| Variable | Producto o método | Límite clave |
| --- | --- | --- |
| Relieve y sombra | LRO/LOLA y LROC para la referencia. Copernicus DEM GLO-30, NASADEM y Sentinel-2 donde haya cobertura terrestre, seguidos de levantamiento fino. | Comparar escalas y resolución efectiva. Un píxel de 5 m puede ser interpolado y uno de decenas de metros en Tierra puede suavizar un obstáculo decisivo. |
| Temperatura y volátiles | Diviner, M³, LCROSS y datos de campaña terrestre | Separar temperatura superficial, estabilidad inferida, detección espectral y medición de muestra. Registrar profundidad, hora, estación y resolución. |
| Regolito y polvo | Medir tamaño y forma de partículas, densidad, tracción y cohesión según la tarea. Ensayar abrasión, adhesión y sellado con simulante y protocolo de hardware. | El polvo terrestre responde a humedad, atmósfera y meteorización. La carga electrostática lunar y la abrasión necesitan condiciones y materiales definidos. |
| Vacío, gravedad, radiación y micrometeoritos | Instalaciones, simulaciones y protocolos de ingeniería según la variable | El ensayo natural caracteriza la operación terrestre. La gravedad lunar es cerca de un sexto de la terrestre; los mecanismos de transferencia térmica, la radiación ionizante y el flujo de impactos requieren modelos o ensayos específicos. |

[NASA PDS, LRO](https://pds-geosciences.wustl.edu/missions/lro/) · [ESA, ficha Copernicus DEM](https://dataspace.copernicus.eu/explore-data/data-collections/copernicus-contributing-missions/collections-description/COP-DEM) · [NASA Earthdata Search](https://search.earthdata.nasa.gov/) · [NASA-STD-1008, ensayos de polvo](https://standards.nasa.gov/standard/nasa/nasa-std-1008) · [NASA, entorno del polo sur lunar](https://www.nasa.gov/reference/moonbase-environment/)

**Ficha del prototipo.** Guardar tarea, región planetaria, polígono o tramo terrestre, criterio con unidad y umbral, dato y resolución, método, comparador, y resultado **cumple / descarta / pendiente** por criterio. La logística y los permisos también pueden determinar si la campaña es viable. La web puede cambiar la recomendación ante un requisito nuevo y mostrar la evidencia responsable del cambio. [Criterios y antecedentes](#estado-del-arte--calidad-de-un-análogo-lunar-o-marciano) · [Prospección terrestre en matydrox.md](matydrox.md#prospección-mundial-de-sitios-terrestres-para-analogías-marcianas)

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

```


## Bitácora de la madrugada · 15 de noviembre de 2026

- **Punto de partida (WhatsApp, 00:35–00:39).** Propuse buscar otro terreno con suelo mixto y repetir la perforación. La idea partía de información imprecisa: confundí el vuelo lunar con uno a Marte y atribuí al taladro lo ocurrido durante el aterrizaje.
- **Corrección.** TRIDENT ya se había probado varias veces y en materiales distintos. En la Luna, Athena quedó de lado y el taladro se accionó sin alcanzar el suelo. El vuelo verificó mecanismos y dejó la perforación pendiente. [NASA Ames, pruebas terrestres](https://ntrs.nasa.gov/citations/20240000585) · [NASA, resultado en la Luna](https://www.nasa.gov/missions/artemis/nasas-lunar-drill-technology-passes-tests-on-the-moon/)
