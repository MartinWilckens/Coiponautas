# Coiponautas
Equipo Coiponautas en el NASA Space Apps Challenge 2026

## Desafío

Queremos identificar sitios en la Tierra donde se puedan simular condiciones de misiones a la Luna y Marte. El foco del equipo es encontrar lugares útiles para ensayar operaciones de una base permanente lunar o marciana. [Recursos del desafío en NASA Space Apps](https://www.spaceappschallenge.org/2026/challenges/permanent-moon-base-locations-and-mars/?tab=resources)

## Estado actual

La pregunta del XMind guía la selección. ¿Qué lugares terrestres menos utilizados podrían cubrir una necesidad específica de una misión análoga, y qué evidencia permite proponerlos? La propuesta es una web que muestre sitios candidatos según los requisitos de la misión. Para cada caso identificamos quién lo necesita, qué tarea quiere ensayar y cuál es su referencia lunar o marciana.

Partimos de una tarea y un ensayo previo para definir requisitos medibles. Cruzamos las capas disponibles por tramo y fecha, indicamos si el sitio cumple, queda fuera o falta información, y verificamos el historial de ensayos, el acceso y las condiciones en terreno.

### Casos preliminares y límites del análogo

En el XMind, las ramas en rojo corresponden a propuestas preliminares que quedaron fuera de la selección por falta de valor adicional demostrado. **El punto donde se rompe la analogía sí va en la respuesta.** Para cada ensayo, indicar qué se reprodujo, qué condición se perdió y qué decisión queda pendiente para una base permanente.

- **TRIDENT · Taladro.** Las pruebas terrestres abarcaron materiales distintos. Reunirlos en un solo sitio quedó fuera por falta de una mejora clara. En la Luna, el aterrizador Athena quedó de lado y el taladro se accionó sin alcanzar el suelo. El ensayo terrestre sirve para caracterizar el desempeño en los materiales probados. La extracción en regolito lunar quedó sin medir. [Pruebas terrestres](https://ntrs.nasa.gov/citations/20240000585) · [Resultado en la Luna](https://www.nasa.gov/missions/artemis/nasas-lunar-drill-technology-passes-tests-on-the-moon/)
- **Polar Explorer · Prospección de hielo.** En LUNA, el radar y la sísmica localizaron acrílico enterrado en simulante. Ahí se pierde parte de la analogía con Haworth, donde interesan el hielo real distribuido en el suelo y el frío polar. Chajnantor quedó como hipótesis preliminar. Falta demostrar que ensayar allí la decisión de dónde perforar aporta valor y verificar zonas con y sin hielo, rutas y acceso. [Ensayo en LUNA](https://www.dlr.de/en/latest/news/2025/water-ice-on-the-moon-simulated-detection-in-the-luna-facility) · [Detalle en neo.md](neo.md)

### Preguntas abiertas

- ¿Qué condiciones queremos reproducir en la Tierra? ¿Cómo las ponderamos y cuáles tienen prioridad según la misión?
- ¿Dónde se realizan misiones análogas actualmente y qué condiciones permiten ensayar esos sitios?
- ¿Qué recursos, condiciones o situaciones quedan por representar en los sitios existentes?

### Fuentes y apuntes de investigación

- Artículos científicos sobre misiones análogas y caracterización de sitios, por recopilar y revisar.
- [Cuaderno de estado del arte](Estado%20del%20arte/state_of_the_art.ipynb) y [cuaderno de recursos](Recursos/resources.ipynb).

### Recursos del desafío

Inventario de los 11 recursos de la copia publicada por HackAthlone, evento local de NASA Space Apps. La pestaña oficial no estuvo accesible durante la revisión. [Listado de HackAthlone](https://hackathlone.com/challenges/permanent-moon-base-locations-and-mars)

| Recurso | Información disponible y uso para Coiponautas |
| --- | --- |
| NASA Earthdata Search | Busca datos terrestres por zona y fecha. Incluye elevación, temperatura superficial, precipitación y cobertura del suelo, útiles para caracterizar sitios candidatos. [Earthdata Search](https://search.earthdata.nasa.gov/) |
| NASA Worldview | Visualiza imágenes y capas satelitales por fecha. Sirve para inspeccionar sitios, nieve estacional y episodios de polvo. [Worldview](https://worldview.earthdata.nasa.gov/) |
| NASA Planetary Data System (PDS) | Archivo de misiones planetarias. Para Marte, MOLA aporta elevación, CRISM aporta firmas espectrales de minerales y SHARAD aporta observaciones de radar del subsuelo. [PDS](https://pds.nasa.gov/) · [Nodo de geociencias](https://pds-geosciences.wustl.edu/) |
| Lunar Reconnaissance Orbiter (LRO) | Para caracterizar una zona lunar, LROC aporta imágenes, LOLA aporta elevación, pendientes y rugosidad, LEND aporta indicios de hidrógeno y Mini-RF aporta imágenes de radar. [Archivo LRO](https://pds-geosciences.wustl.edu/missions/lro/) |
| LRO Diviner Lunar Data | Mapas de temperatura superficial lunar. Permiten estimar dónde podría persistir el hielo por estabilidad térmica. [Diviner](https://pds-geosciences.wustl.edu/missions/lro/diviner.htm) |
| RADARSAT Constellation Mission (CSA) | Imágenes de radar adquiridas de día o de noche, incluso con nubosidad. Útiles para explorar hielo, humedales y cambios de superficie. [Datos RCM](https://donnees-data.asc-csa.gc.ca/en/dataset/rcm) |
| RADARSAT-1 (CSA) | Archivo histórico abierto de imágenes de radar. Permite comparar escenas antiguas donde haya cobertura. [Datos RADARSAT-1](https://donnees-data.asc-csa.gc.ca/en/dataset/radarsat1) |
| Tutorial SAR en Python y QGIS (CSA) | Código y ejemplos para abrir y visualizar imágenes RADARSAT como capas de trabajo. [Tutorial de la CSA](https://github.com/asc-csa/Synthetic_Aperture_Radar_Tutorial) |
| Copernicus Data Space Ecosystem | Sentinel-1 aporta radar, Sentinel-2 aporta imágenes multiespectrales y Copernicus DEM aporta elevación. Sirve para medir pendientes y distinguir agua, vegetación y suelo expuesto. [Copernicus Data Space](https://dataspace.copernicus.eu/) |
| ESA Open Science Catalog | Catálogo de productos, estudios y flujos de trabajo de observación terrestre. Las fichas ayudan a revisar metodología, cobertura, resolución y enlaces al proveedor. [Catálogo ESA](https://opensciencedata.esa.int/products/catalog) |
| JAXA G-Portal | Busca observaciones terrestres por variables como precipitación, nieve y vegetación. Permite estudiar la aridez y los cambios estacionales según el producto elegido. [JAXA G-Portal](https://www.gportal.jaxa.jp/?lang=en) |

Para las preguntas base, estas fuentes permiten identificar qué condiciones podemos medir y qué queda por validar. Por ejemplo, LOLA y Copernicus DEM permiten comparar pendientes a escalas compatibles, mientras que evaluar la tracción de un rover requiere datos del suelo o ensayos de campo. Para saber dónde se han realizado misiones análogas y qué se ensayó, consulta los informes de cada campaña. [Misiones análogas de NASA](https://www.nasa.gov/analog-missions/)

## Trabajo en equipo y con asistentes de IA

Cada integrante lleva sus avances en un Markdown con su alias en la raíz del repositorio, como [`neo.md`](neo.md). Al incorporar un sitio candidato o un criterio, deja la fuente, explica qué condición de la misión ayuda a evaluar e indica qué falta validar. Para retomar el trabajo con un asistente de IA, usa este archivo, los cuadernos y el Markdown del integrante como contexto. Los criterios, sus pesos y los sitios candidatos siguen abiertos a la investigación del equipo.
