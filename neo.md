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
