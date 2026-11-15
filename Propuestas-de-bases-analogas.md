# Propuestas de bases análogas: sitios, datos y brechas

Documento vivo para comparar lugares terrestres que podrían albergar campañas o instalaciones análogas lunares o marcianas. Una **base análoga** aquí significa una estación o infraestructura de ensayo en la Tierra; no implica que el sitio sea apto para una base espacial real ni que ya se haya probado una base permanente allí.

## Cómo usar y ampliar este documento

- Mantener una ficha por sitio y separar **observaciones publicadas**, **datos preliminares del mapa** e **hipótesis de trabajo**.
- No presentar una condición regional como medición del punto. Guardar fuente, fecha/periodo, método, escala o resolución y ubicación de cada dato.
- Registrar coordenadas en WGS84 como latitud, longitud; incluir incertidumbre y qué representa el punto (entrada de cueva, estación, muestra, centro del salar, etc.).
- Identificar el ensayo que se quiere hacer. La similitud debe referirse a una propiedad o tarea concreta, no a que el lugar «es igual» a la Luna o Marte.
- Antes de proponer instalación o campaña, verificar permisos, titularidad, protección cultural y ambiental, acceso, seguridad y gestión de residuos.
- Completar los campos con `Documentado`, `Preliminar (mapa)`, `Pendiente` o `No aplica`. Añadir enlaces a fuentes primarias siempre que sea posible.

### Plantilla para nuevos sitios

```md
## [Nombre del sitio] · [región, país]

**Estado:** candidato / campaña documentada / instalación existente  
**Objetivo de la base o campaña:** [tarea concreta]  
**Cuerpo de comparación:** Luna / Marte / ambos  
**Ubicación:** [coordenadas, datum, precisión, qué punto representan]  
**Área y altitud:** [valor, unidad, método/fuente]  
**Datos ambientales:** [parámetro, valor, periodo, escala y fuente]  
**Geología y materiales:** [litología, mineralogía, suelos, cavidades, agua/hielo]  
**A qué se asimila:** [propiedad/tarea y límites de la comparación]  
**Datos disponibles:** [estudios, mapas, imágenes, campañas]  
**Datos que falta caracterizar:** [medición necesaria y escala]  
**Desafíos para instalar una base análoga:** [ingeniería, operación, acceso, ambiente y seguridad]  
**Permisos y resguardos:** [autoridades, patrimonio, comunidades, ecosistemas]  
**Fuentes:** [enlaces y localizadores]
```

---

## Túneles de lava de Ana Te Pahu · Rapa Nui, Chile

**Estado:** candidato preliminar; la idoneidad del sector y la posibilidad de instalar infraestructura no están demostradas.  
**Objetivo propuesto:** evaluar una campaña de reconocimiento no invasivo y, si la administración del sitio lo permite, ensayar cartografía, movilidad, comunicaciones y operaciones humanas en un tubo de lava.  
**Cuerpo de comparación:** Luna y Marte, en lo relativo a cavidades volcánicas y operaciones subterráneas.

### Datos disponibles

| Campo | Dato | Estado y observación |
| --- | --- | --- |
| Sitio nombrado en el mapa | Tubos de lava de Ana Te Pahu | Identificación preliminar del mapa compartido; confirmar qué tubo/sector es el candidato. |
| Coordenadas | 27°06′47,9″ S, 109°24′49,9″ O (aprox. −27.113306, −109.413861) | Preliminar del mapa. No está verificada como entrada ni como área útil; validar datum, precisión y permisos antes de usar. |
| Temperatura anual promedio | 20–21 °C | Valor preliminar del mapa; faltan estación, periodo, método y escala espacial. No asumir que representa el interior del tubo. |
| Humedad relativa | 100 % | Valor preliminar del mapa; faltan punto, periodo y método. Medir dentro y fuera de la cavidad y en distintas estaciones. |
| Geología general | Tubos de lava volcánica; hay estudios de espeleotemas silíceos en tubos de Rapa Nui | El repositorio identifica espeleotemas silíceos y propone cavidades basálticas como comparación de tubos lunares y marcianos. No se deben extrapolar esos resultados al tubo exacto sin ubicar el muestreo. [EANA 2025, resumen sobre espeleotemas](https://eana-net.eu/conferences/EANA2025/abstract_show.php?id=141) · [Coiponautas, propuesta previa](https://github.com/MartinWilckens/Coiponautas/blob/main/luvsichexalogy.md) |
| Mapa 3D continuo | No disponible en la ficha del mapa | Pendiente; obtener modelo con cobertura, resolución, sistema de coordenadas y control de calidad adecuados. |
| Estabilidad | Sin caracterización del techo, paredes ni bloques para el sector | Pendiente; levantamiento geológico/geotécnico por especialistas. |
| Antecedente análogo en ese sitio | No identificado en la búsqueda consignada por el repositorio | No equivale a demostrar que nunca hubo campañas. Actualizar búsqueda bibliográfica y con autoridades locales. |

### A qué se asimila y qué sí permitiría estudiar

Se asimila a **tubos de lava lunares o marcianos como posibles refugios subterráneos**. El valor analógico está en las operaciones y la geología: movilidad en pasajes confinados, cartografía, navegación robótica, comunicaciones dentro de una cavidad, observación de paredes y estudio de espeleotemas. Es un análogo **geológico y operacional parcial**. No reproduce la gravedad, vacío, radiación, temperatura ni composición atmosférica de la Luna o Marte; la humedad de la cueva tampoco debe confundirse con esas condiciones.

### Datos que falta caracterizar

- Geometría y continuidad: modelo 3D del tubo, largo, ancho, altura, ramificaciones, entradas, estrechamientos, desniveles y volumen utilizable.
- Seguridad geotécnica: espesor/estado del techo cuando sea medible, fracturas, desprendimientos, bloques, inundación y evaluación de riesgo de colapso. Definir zonas excluidas.
- Ambiente: series de temperatura, humedad, ventilación, CO₂, O₂, radón u otros gases pertinentes, agua/filtración y variación estacional; medir dentro y fuera con sensores calibrados.
- Superficie y operaciones: rugosidad, obstáculos, barro/agua, iluminación, polvo, puntos de anclaje y capacidad de carga del piso.
- Comunicaciones: atenuación de radio, enlaces a la entrada, repetidores, navegación sin GNSS y procedimiento de rescate.
- Ecología y patrimonio: inventario de organismos, microhábitats, espeleotemas, elementos arqueológicos/culturales y áreas de sensibilidad antes de cualquier visita de investigación.
- Logística: acceso y evacuación, transporte de equipos, energía, agua, saneamiento, comunicaciones exteriores y respuesta médica.

### Desafíos para instalar una base análoga

- **Primero, demostrar que el emplazamiento admite una instalación sin daño.** El mapa propone identificar sectores arqueológicos, culturales o biológicos para excluirlos y permitir, si corresponde, una visita científica sin intervención. La instalación física puede no ser autorizable.
- Evitar perforaciones, anclajes, iluminación permanente, tránsito repetido, extracción de muestras o alteración de espeleotemas sin autorización expresa y evaluación de impacto.
- Resolver humedad cercana a saturación, condensación, corrosión, control de moho/contaminación, ventilación y protección eléctrica; los valores del mapa aún no son mediciones verificadas del interior.
- Garantizar estabilidad, evacuación y rescate en un entorno confinado; no instalar módulos antes de contar con evaluación geotécnica y plan de emergencia.
- Diseñar energía, comunicaciones, acceso y manejo de residuos sin bloquear pasajes ni degradar el lugar.
- Acordar gobernanza con las autoridades y comunidades de Rapa Nui; confirmar régimen de protección, permisos de ingreso y límites para investigación arqueológica, biológica y geológica.

### Fuentes y límites

- [EANA 2025 · resumen sobre espeleotemas de tubos de lava de Lanzarote, Rapa Nui, La Palma y Galápagos](https://eana-net.eu/conferences/EANA2025/abstract_show.php?id=141).
- [Coiponautas · propuesta previa para túneles de lava de Rapa Nui](https://github.com/MartinWilckens/Coiponautas/blob/main/luvsichexalogy.md#análogos-terrestres-propuestos-lugares-y-brechas).
- Coordenadas, temperatura y humedad de esta ficha se transcribieron del mapa aportado por el usuario y siguen **sin verificación independiente**.

---

## Salar de Pajonales · Antofagasta, norte de Chile

**Estado:** candidato a campañas de caracterización y ensayos específicos; el sitio ya tiene antecedentes científicos, pero no se identificó en el repositorio una base instalada.  
**Objetivo propuesto:** caracterizar costras y minerales evaporíticos; evaluar, como hipótesis de ensayo, la extracción de agua de minerales hidratados y el balance energético del proceso. Esta propuesta de extracción no se debe describir como un ensayo ya realizado en Pajonales.  
**Cuerpo de comparación:** principalmente Marte; útil también para estudiar cómo se reconocen evaporitas mediante teledetección y trabajo de campo.

### Datos disponibles

| Campo | Dato | Estado y observación |
| --- | --- | --- |
| Área | 104 km² | Valor recopilado en el repositorio. Precisar si es superficie total del salar o polígono de estudio al comparar estudios. [Coiponautas, propuesta previa](https://github.com/MartinWilckens/Coiponautas/blob/main/luvsichexalogy.md) |
| Coordenadas de referencia | 25.4149° S, 68.77215° O (aprox. −25.4149, −68.77215) | Preliminar del mapa. No identificar como estación, muestra o polígono sin confirmar. Georreferenciar cada transecto y muestra. |
| Altitud | 3.500 m | Preliminar del mapa, aparentemente redondeado; contrastar con DEM y ubicación exacta. |
| Temperatura promedio | 5 °C | Preliminar del mapa; no consta periodo, estación ni método. Requiere serie local y extremos diarios/estacionales. |
| Tipo de salar | Salar andino de sulfato de calcio | Caracterización resumida en el repositorio; confirmar mineralogía por unidad y sector. [Flahaut et al. (2017)](https://sshade.eu/data/publication/PUBLI_Flahaut_2017) |
| Costra | Los sulfatos forman parte principal de las costras de salares andinos | Resultado regional citado por Coiponautas; no asumir composición uniforme en todo Pajonales. [Coiponautas, referencias a Flahaut et al. (2017) y Hinman et al. (2022)](https://github.com/MartinWilckens/Coiponautas/blob/main/luvsichexalogy.md) |
| Biofirmas | Hay antecedentes que combinan imágenes orbitales, drones y muestras para orientar la búsqueda de biofirmas en Pajonales | Antecedente de investigación, no prueba de habitabilidad ni de que todas las zonas sean estériles. [Warren-Rhodes et al. (2023)](https://doi.org/10.1038/s41550-022-01882-x) |
| Datos del mapa aún faltantes | Distribución y profundidad local del recurso hídrico; resistencia de costra y subsuelo; respuesta a vehículos, módulos, anclajes y cargas repetidas; viento, polvo, UV y temperatura del subsuelo | Pendientes explícitos en el mapa compartido. |

### A qué se asimila y qué sí permitiría estudiar

Se asimila a **depósitos evaporíticos y minerales de sulfato de calcio de Marte**: permite investigar morfologías de costras, mineralogía, alteración, detección remota y validación con muestras. La tarea exploratoria añadida al mapa es comprobar si ciertos minerales hidratados pueden aportar agua y medir el consumo energético del proceso; esto es una **propuesta de ensayo**, que requiere confirmar primero qué minerales hidratados están presentes, su abundancia y su agua estructural.

La comparación es de materiales y procesos geológicos concretos; no reproduce por sí sola la atmósfera, gravedad, radiación, temperatura ni condiciones de operación marcianas. Los valores de 5 °C y 3.500 m del mapa requieren confirmar localización y periodo antes de usarlos en un diseño.

### Datos que falta caracterizar

- Cartografía por unidades: polígono del salar, costra, depósitos marginales, zonas húmedas/seca, transectos y ubicación/depth de cada muestra; DEM con resolución y error conocidos.
- Mineralogía cuantitativa y distribución espacial: fases de sulfato, grado de hidratación, mezclas, granulometría, porosidad, densidad y variación entre costra y subsuelo.
- Agua: presencia superficial/subsuperficial, profundidad, salinidad, extensión, estacionalidad y origen. Separar agua libre, hielo si lo hubiera y agua ligada a minerales.
- Geotecnia: espesor y resistencia de la costra, capacidad de carga, hundimiento, fractura, abrasión, vibración y respuesta a cargas estáticas/dinámicas; ensayar fuera de zonas sensibles.
- Ambiente local: series de temperatura de aire y suelo, humedad, presión, viento, radiación UV, polvo, visibilidad y extremos; datos por estación y altura/profundidad.
- Ensayo de extracción (si la mineralogía lo justifica): rendimiento de agua por masa de mineral, temperatura y energía específica, equipos, residuos, emisiones, recuperación del agua y comparación con controles.
- Microbiología/ecología: línea base espacial y temporal, zonas de exclusión y riesgo de contaminación cruzada; el tránsito, perforación o calentamiento puede destruir señales que se pretende estudiar.
- Operación: rutas, pendientes, polvo, agua para consumo, energía, comunicación, evacuación, soporte médico y ventanas climáticas.

### Desafíos para instalar una base análoga

- Altitud cercana a 3.500 m (valor preliminar del mapa) añade exigencias fisiológicas y operativas; caracterizar presión y aclimatación del equipo y definir protocolos médicos.
- Resolver frío, viento, radiación UV, polvo y grandes variaciones térmicas con módulos aislados, energía y sistemas de seguridad diseñados para el sitio.
- Verificar si la costra soporta tránsito y módulos. Vehículos, cargas repetidas, anclajes y perforaciones podrían romperla o alterar la estratigrafía; diseñar acceso de bajo impacto y zonas de prueba delimitadas.
- Proteger lagunas, comunidades microbianas y posibles biofirmas frente al tránsito, extracción, calor, residuos y contaminación humana. Establecer línea base, áreas de control y límites de intervención antes de desplegar equipo.
- Confirmar agua y energía disponibles sin inferir que el agua mineral es un recurso explotable: extraerla puede requerir mucha energía y dejar residuos; primero corresponde medir el balance material y energético a escala de laboratorio.
- Confirmar accesos, propiedad, concesiones, permisos ambientales y de investigación, y coordinación con organismos públicos y comunidades pertinentes antes de construir o desplegar una estación.

### Fuentes y límites

- [Warren-Rhodes et al. (2023) · búsqueda de biofirmas en Salar de Pajonales](https://doi.org/10.1038/s41550-022-01882-x).
- [Hinman et al. (2022) · morfologías superficiales en un salar de sulfato de calcio análogo de Marte](https://doi.org/10.3389/fspas.2021.797591).
- [Flahaut et al. (2017) · teledetección y reconocimiento mineralógico de salares chilenos](https://sshade.eu/data/publication/PUBLI_Flahaut_2017).
- [Coiponautas · resumen previo de la propuesta y brechas](https://github.com/MartinWilckens/Coiponautas/blob/main/luvsichexalogy.md#análogos-terrestres-propuestos-lugares-y-brechas).
- Coordenadas, altitud y temperatura son transcripciones preliminares del mapa aportado por el usuario; el área y contexto geológico proceden del trabajo ya recopilado en el repositorio. Verificar el polígono y las fuentes originales antes de tratarlos como datos de ingeniería.

---

## Registro de cambios

| Fecha | Cambio |
| --- | --- |
| 2026-11-15 | Ficha inicial para los túneles de lava de Ana Te Pahu y el Salar de Pajonales, basada en el mapa aportado y en las fuentes ya recopiladas por Coiponautas. |
