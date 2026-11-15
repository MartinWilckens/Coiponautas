# Conexión de nuestros análogos con la exploración · Coiponautas

**NASA Space Apps Challenge 2026 · 15 de noviembre de 2026**

Este documento responde al punto del desafío:

> *Conecta tu analógico con la exploración. Explica cómo la ubicación o proceso que identifiques podría ayudar a científicos e ingenieros a entender la Luna, Marte o ambos; probar instrumentos o tecnologías, preparar operaciones robóticas o humanas; buscar recursos o señales de habitabilidad; o reducir los riesgos de exploración.*

Revisa las ubicaciones que hay en el repositorio a la fecha (atlas `Coiponautas-Atlas-Interactivo.html` del commit `9cebd2c`, `Inventario-Coiponautas-sitios-y-datos-pendientes.md`, `neo.md`, `matydrox.md` y `luvsichexalogy.md`). Pone el foco en los lugares **propuestos por el equipo**. Las cifras provienen de esos archivos y de las fuentes que citan. Lo que es idea nuestra y no figura ensayado en las fuentes se marca como **propuesta**.

---

## 1. Qué ubicaciones hay hoy en el repositorio

| Grupo | Sitios | Dónde están |
| --- | --- | --- |
| **Propuestas del equipo, en el atlas** | Pali-Aike (Chile) · Chajnantor, sondeo B3 (Chile) | Atlas, inventario. Pali-Aike en una versión anterior de `neo.md` (commit `f6e9002`); B3 en `neo.md` |
| **Candidatos documentales del atlas** (reunidos por el equipo a partir de la literatura) | Saskylakh (Rusia) · Lake Yamma Yamma (Australia) · Bhallil (Marruecos) · Williams Point (Australia) · Salada de Chiprana (España) · Aucanquilcha (Chile) · Laguna Miscanti (Chile) · Quinamávida (Chile) | Atlas, inventario |
| **Propuestas nuevas, aún fuera del atlas** | Stefánshellir–Surtshellir (Islandia) · La Corona y Cueva de los Naturalistas (Lanzarote) · Túneles de lava de Rapa Nui (Chile) · Salares andinos de sulfato de calcio, p. ej. Pajonales (Chile) | `luvsichexalogy.md`, «Análogos terrestres propuestos» |
| **Antecedentes conocidos** (comparadores, no candidatos) | LUNA, Colonia (ESA/DLR) · Lanzarote, PANGAEA (ESA) | Atlas |
| **Compilación histórica** | 66 sitios de campañas existentes | Inventario, `luvsichexalogy.md` |

Las referencias planetarias que usa el equipo son **Luna:** de Gerlache Rim 2, Haworth, Macizo Malapert y el pozo de Mare Tranquillitatis. **Marte:** Arcadia–Amazonis, Jezero, Gale y Oxia Planum.

---

## 2. Matriz: qué aporta cada análogo a la exploración

Columnas según el desafío. **●** = aporte principal; **○** = aporte secundario o que depende de completar datos.

| Sitio | Referencia | Entender | Probar instrumentos | Preparar operaciones | Recursos / habitabilidad | Reducir riesgos |
| --- | --- | :-: | :-: | :-: | :-: | :-: |
| **Pali-Aike** | Luna · de Gerlache Rim 2 | ○ | ● | ● | | ● |
| **Chajnantor B3** | Luna · Haworth | ○ | ● | ● | ● | ● |
| Aucanquilcha | Marte · Arcadia–Amazonis | ○ | ● | ○ | ● | ● |
| Saskylakh | Marte · Arcadia–Amazonis | ● | ○ | ● | ● | ○ |
| Laguna Miscanti | Marte · Jezero | ● | ○ | ○ | ● | |
| Lake Yamma Yamma | Marte · Jezero | ● | | ● | ○ | ○ |
| Williams Point | Marte · Gale | ● | ● | ○ | ○ | |
| Salada de Chiprana | Marte · Gale | ● | ○ | | ● | |
| Bhallil | Marte · Oxia Planum | ● | ● | ○ | ● | ○ |
| Quinamávida | Marte · Oxia Planum | ○ | ● | | ○ | ● |
| Salares de sulfato (Pajonales) | Marte · Melas Chasma / Valles Marineris | ○ | ● | | ● | ○ |
| Stefánshellir–Surtshellir | Luna y Marte · tubos de lava | | ○ | ● | ○ | ● |
| La Corona / Naturalistas | Luna · pozo de Mare Tranquillitatis | ● | ● | ○ | | ● |
| Túneles de Rapa Nui | Luna y Marte · tubos de lava | ○ | | ○ | ○ | ○ |

---

## 3. Propuestas del equipo

### 3.1 Pali-Aike, Magallanes → Luna · de Gerlache Rim 2

**La conexión.** En el borde de de Gerlache Rim 2 (≈88,2° S), el Sol está siempre cerca del horizonte. Las sombras largas cambian con el azimut y esconden obstáculos. El cono de Pali-Aike tiene un cráter de 160–180 m, paredes de 40–45° y pendientes de 10–22° hacia la base (Sernageomin). A 52° S, el Sol tarda unos 33 a 46 min en subir de 0° a 5°, según la estación. Eso da ventanas cortas y repetibles de luz rasante sobre un relieve con sombras marcadas.

- **Probar instrumentos o tecnologías.** Sirve para probar cámaras, iluminadores y algoritmos de detección de obstáculos con el Sol bajo y transiciones de luz a sombra.
- **Preparar operaciones robóticas o humanas.** Sirve para planificar rutas de rover o EVA según la geometría del Sol y para medir cuánto tarda el sistema en recuperarse al entrar en sombra.
- **Reducir riesgos.** Permite cuantificar cuántos obstáculos pasan inadvertidos con luz rasante antes de conducir en el polo sur, donde un error de percepción puede inmovilizar el vehículo.

**Ensayo y métrica (propuesta).** Recorrer el mismo tramo con luz de referencia y con luz rasante. Medir los obstáculos detectados y los omitidos frente a un levantamiento independiente, el error de posición, las paradas y el tiempo de recuperación. La ventaja que se busca frente a ERNEST (JPL, desierto de Colorado) es **más transiciones útiles de luz a sombra por cada 100 m transitables**. LUNA permite repetir el ensayo con ángulo y contraste controlados.

**Dónde se rompe.** La atmósfera terrestre dispersa luz hacia las sombras, y la Luna tiene otra gravedad, no tiene atmósfera y su regolito es distinto. Copernicus GLO-30 representa el cráter con solo 5–6 celdas, por lo que se necesita fotogrametría o un levantamiento local para trabajar a escala de rover. El parque es de CONAF y salir de los senderos requiere permiso.

### 3.2 Chajnantor, sondeo B3 → Luna · Haworth

**La conexión.** Haworth es una de las regiones de aterrizaje de Artemis con acceso a sombra permanente. M³ ve firmas compatibles con hielo en su superficie, pero se desconoce cuánto hielo hay y a qué profundidad. En B3 (−22,990278°, −67,728889°; ≈5.075 m) hay suelo volcánico fino cementado por hielo: 46 % en volumen de 0 a 2 m y 66 % de 2 a 4 m. Los sondeos B4 y B5, en el mismo volcán, se clasificaron sin permafrost. Así hay **puntos con hielo y puntos sin hielo documentados** dentro del mismo terreno.

- **Probar instrumentos o tecnologías.** Permite probar radar de subsuelo, sísmica y sondas de neutrones o de humedad con un resultado conocido de antemano.
- **Preparar operaciones robóticas.** Un rover decide dónde perforar a partir de mapas de baja resolución y lecturas de radar, como lo haría en el fondo de Haworth.
- **Buscar recursos.** Ensaya la primera decisión de una base: dónde está el agua, a qué profundidad y en qué cantidad. Según la VIPER, esa agua podría dar agua potable y oxígeno.
- **Reducir riesgos.** Permite medir cuántas perforaciones caen en puntos sin hielo y cuánto se equivoca la profundidad estimada. Un sensor que confunde una capa seca con hielo gasta tiempo, energía y broca.

**Ensayo y métrica (propuesta).** Hacer sondeos de verificación cuyos resultados se mantienen ocultos durante el ensayo. Medir los falsos positivos de perforación, el error de profundidad y la capacidad de llegar al punto elegido y muestrear. Polar Explorer (DLR/ESA, en LUNA) usó blancos de acrílico. B3 aporta **hielo real mezclado con suelo**.

**Dónde se rompe.** Diviner da 20–45 K en el fondo de Haworth. La mínima más baja estimada en Chajnantor durante 2025 fue −14,1 °C (NASA POWER). Tampoco se reproducen el vacío ni la oscuridad, y el frío y la sublimación se ensayarían en cámara. Falta confirmar la distribución del hielo, las rutas y el acceso.

### 3.3 Salares andinos de sulfato de calcio (Pajonales) → Marte · Melas Chasma / Valles Marineris

**La conexión.** Cerca del ecuador marciano, el agua no está en forma de hielo somero sino unida a minerales hidratados como los sulfatos. Pajonales es un salar de sulfato de calcio de 104 km². Flahaut et al. (2017) encontraron que los sulfatos forman la costra principal de los salares andinos.

- **Buscar recursos.** **Propuesta nuestra:** deshidratar el mineral y medir la **energía por litro de agua**. Sería un dato para decidir si una base de baja latitud puede abastecerse de minerales en lugar de hielo. Las fuentes no muestran este ensayo realizado.
- **Probar instrumentos.** Permite comparar espectrómetros de campo y orbitales sobre la misma costra, a escalas distintas.
- **Habitabilidad.** Pajonales ya figura en `neo.md` para buscar biofirmas en evaporitas.

**Dónde se rompe.** Los sulfatos marcianos y su grado de hidratación tienen que compararse fase por fase. Falta confirmar el acceso y los permisos.

### 3.4 Stefánshellir–Surtshellir, Islandia → Luna y Marte · tubos de lava como refugio

**La conexión.** Los tubos de lava lunares y marcianos se estudian como refugio contra la radiación, los micrometeoritos y los cambios térmicos. Horvath et al. estimaron ≈17 °C en el interior sombreado de una cavidad lunar modelada. EuroMoonMars eligió Stefánshellir–Surtshellir en 2018 como el mejor candidato para una base análoga lunar, y CHILL-ICE construyó allí un hábitat.

- **Preparar operaciones humanas.** Permite ensayar la tarea de vivir y trabajar dentro de la cavidad, no solo cartografiarla.
- **Reducir riesgos.** Permite ensayar la logística de entrada y salida, las comunicaciones del interior al exterior, la evacuación y el montaje del hábitat.

**Dónde se rompe.** No reproduce la gravedad, el vacío ni la radiación. Ya tiene campañas, por lo que su aporte es la tarea y no la novedad del sitio.

### 3.5 La Corona y Cueva de los Naturalistas, Lanzarote → Luna · pozo de Mare Tranquillitatis

**La conexión.** El radar Mini-RF sugiere un conducto bajo el borde occidental del pozo de Mare Tranquillitatis, pero se desconocen su extensión y su estabilidad. En Naturalistas, un estudio de 2026 combinó sísmica, magnetometría y gravimetría para detectar cavidades desde la superficie. La Corona tiene un tubo de unos 7,6 km de largo y 30 m de ancho.

- **Entender la Luna.** Ayuda a interpretar qué señal geofísica deja un tubo de lava conocido antes de interpretar una lunar.
- **Probar instrumentos.** Permite calibrar métodos de detección superficial con la geometría real del tubo como verdad de terreno.
- **Reducir riesgos.** Permite saber si existe un conducto, y si es estable, antes de enviar un robot o una tripulación.

**Dónde se rompe.** Lanzarote ya es sede de PANGAEA y PANGAEA-X. Cueva de los Verdes se usó para mapeo robótico, por lo que el aporte nuevo es la detección desde la superficie.

### 3.6 Túneles de lava de Rapa Nui, Chile → Luna y Marte · cavidades basálticas (por verificar)

**La conexión.** Son tubos basálticos estudiados por sus espeleotemas silíceos. Podrían servir para ensayar la base subterránea en un sitio chileno.

- **Habitabilidad (hipótesis).** Los depósitos silíceos en cavidades pueden preservar señales minerales o biológicas. Falta respaldarlo para este sitio.
- **Pendiente.** No hay uso previo documentado como análogo, y eso no prueba que no exista. Faltan los permisos, el acceso y el estado de protección del sitio. Hoy no conviene presentarlo como candidato firme.

---

## 4. Candidatos documentales del atlas

### 4.1 Aucanquilcha, Chile → Marte · Arcadia–Amazonis

**La conexión.** SWIM cartografía en Arcadia–Amazonis evidencias de hielo subsuperficial y las presenta como un recurso para futuras misiones (USGS, 2021; NASA, 2023). La estación A1 de Aucanquilcha, a 5.100 m, tiene una temperatura media anual del suelo de 1,97 °C y **no se detectó permafrost** en 2023.

- **Reducir riesgos y probar instrumentos.** Su aporte más claro es servir de **control seco** en altura. Junto con Chajnantor B3, que tiene hielo, forma un par positivo/negativo para medir falsos positivos de un detector de hielo. Ambos sitios proceden del mismo estudio multisitio (Yoshikawa et al., 2025) (**propuesta**).
- **Recursos.** Si se confirma hielo en A2 o en la cumbre, serviría para ensayar perforación en material volcánico con hielo.

**Dónde se rompe.** Faltan las coordenadas y los resultados de A2 y de la cumbre. La presencia física de hielo requiere revisión local.

### 4.2 Saskylakh, Rusia → Marte · Arcadia–Amazonis

**La conexión.** AP-1, en Arcadia, es una llanura con microrelieve poligonal ligado a hielo subsuperficial. Saskylakh tiene un campo poligonal de 12,84 km² con una capa activa estimada de 0,56–0,665 m.

- **Entender Marte.** Ayuda a interpretar el mecanismo que forma polígonos con hielo. Hay que documentarlo, porque no todo patrón poligonal tiene el mismo origen.
- **Preparar operaciones.** Permite navegar y muestrear sobre microrelieve poligonal con una geometría de obstáculos comparable.
- **Recursos.** Permite verificar la profundidad del hielo bajo la capa activa, con sondeos y controles secos.

**Dónde se rompe.** La capa activa procede de un modelo de 1 km y no se ha medido en terreno. La ubicación es regional y aproximada. Además, el permafrost siberiano tiene vegetación y agua estacional que Arcadia no tiene.

### 4.3 Laguna Miscanti, Chile → Marte · Jezero

**La conexión.** Jezero tiene un delta, un paleolago y carbonatos. Miscanti es un lago a 4.140 m, de 13,5 km² y 9,68 m de profundidad en el punto del testigo, con conductividad de 6,4–6,9 mS/cm, pH 8–8,8, abanicos y depósitos marginales.

- **Entender Marte.** Permite ver cómo se depositan facies lacustres y de margen en un lago salino de altura.
- **Habitabilidad.** Sirve para estudiar la preservación y la detectabilidad de señales en sedimentos lacustres finos, la pregunta que guía la selección de muestras de Perseverance.

**Dónde se rompe.** La equivalencia entre un abanico y un delta requiere evidencia sedimentológica. Para muestrear dentro de la Reserva Los Flamencos hace falta una autorización aparte de CONAF.

### 4.4 Lake Yamma Yamma, Australia → Marte · Jezero

**La conexión.** Es un delta y humedal efímero de 866 km², con inundación estacional (DIWA) y sedimentología publicada.

- **Preparar operaciones.** Permite repetir el tipo de ensayo de CanMars (Utah): un equipo remoto elige muestras a lo largo de un delta, y luego sus decisiones se contrastan con laboratorio.
- **Entender Marte.** Comparar fechas húmedas y secas muestra cómo cambia un delta cuando el agua desaparece.

**Dónde se rompe.** El polígono oficial es el humedal y falta delimitar el delta nororiental. Tampoco hay datos de granulometría ni de microrelieve de la ruta.

### 4.5 Williams Point, Australia → Marte · Gale

**La conexión.** Gale registra lagos, agua subterránea e intervalos eólicos con humedecimiento periódico. Williams Point expone unidades lacustres, fluvio-lacustres y eólicas, estudiadas con OSL, DRX y FRX.

- **Entender Marte.** Ayuda a leer el cambio de un ambiente lacustre a uno eólico en una misma secuencia.
- **Probar instrumentos.** DRX y FRX son el mismo tipo de técnica que CheMin y APXS de Curiosity. Se puede comparar lo que ve el instrumento de campo con el análisis de laboratorio en cada nivel.

**Dónde se rompe.** La coordenada disponible corresponde a una foto de contexto, no a la columna estratigráfica. Además, la diagénesis de Gale es propia de ese cráter.

### 4.6 Salada de Chiprana, España → Marte · Gale

**La conexión.** Es una laguna hipersalina permanente con salmuera, paleosuelos y facies lacustres y eólicas. Encaja con la transición de arcillas a sulfatos de Gale, donde se interpretan fluidos salinos posteriores al depósito.

- **Habitabilidad.** Permite estudiar la preservación de compuestos y la vida microbiana en salmueras y sales, que en el atlas figura como tarea de astrobiología.
- **Entender Marte.** Muestra cómo las sales se distribuyen por estrato.

**Dónde se rompe.** Faltan la especie mineral por estrato y la ubicación de los perfiles. Es una Reserva Natural Dirigida, por lo que muestrear requiere autorización.

### 4.7 Bhallil, Marruecos → Marte · Oxia Planum

**La conexión.** Oxia tiene arcillas antiguas y es el destino de Rosalind Franklin, cuyo taladro alcanzará hasta 2 m. Bhallil tiene un perfil de alteración de 10 m sobre metabasalto, con esmectita y clorita-esmectita en tres facies.

- **Probar instrumentos.** Permite perforar 2 m en un perfil arcilloso y comparar la mineralogía con la profundidad, con Raman y DRX, como hizo ExoFiT en Atacama.
- **Habitabilidad.** Ayuda a evaluar si conviene perforar más profundo para encontrar material menos alterado, la misma decisión que tomará el rover.
- **Entender Marte.** Muestra cómo cambia la alteración de un basalto con la profundidad.

**Dónde se rompe.** No hay coordenadas del perfil, que se describe como «unos 15 km al SE de Fez», por lo que el filtro climático del atlas no se puede aplicar. Las arcillas de Oxia deben compararse afloramiento por afloramiento.

### 4.8 Quinamávida, Chile → Marte · Oxia Planum

**La conexión.** Son tobas con zeolitas (mordenita, clinoptilolita, heulandita) y esmectita variable. El atlas las presenta como contraste mineralógico.

- **Probar instrumentos y reducir riesgos.** Sirve para comprobar si un espectrómetro distingue zeolita de esmectita. Si las confunde, puede llevar a interpretar mal la historia del agua y a elegir mal el punto de perforación (**propuesta**).
- **Pendiente.** Hay que respaldar con una fuente qué zeolitas se han reportado en Marte.

**Dónde se rompe.** La analogía es mineralógica y parcial. Tampoco se ha ubicado el perfil de tobas.

---

## 5. Antecedentes que usamos como comparadores

- **LUNA (Colonia).** Tiene 700 m² de simulante con al menos 0,6 m de espesor, un simulador solar y un sismómetro permanente. Es donde se repiten, con condiciones controladas, los ensayos de Pali-Aike (luz rasante) y Chajnantor (detección de hielo). Lo que aporta el campo es el **terreno real**; lo que aporta LUNA es la **repetibilidad**.
- **Lanzarote · PANGAEA.** Entrenamiento geológico de astronautas en Caldera Blanca. Cueva de los Verdes (PANGAEA-X) es el comparador de cartografía de cavidades para Mare Tranquillitatis.

---

## 6. Hallazgos de la revisión de datos

1. **La fuente de la ficha de Pali-Aike en el atlas apunta a un commit antiguo de `neo.md` (`f6e9002`).** El `neo.md` actual ya no tiene la sección del piloto de Pali-Aike, que incluía la ventana de 17 × 17 celdas, el cálculo de 33–46 min y la métrica de transiciones por 100 m. Conviene restaurarla en el `neo.md` actual o en el inventario.
2. **Las cuatro propuestas nuevas de `luvsichexalogy.md` no están en el atlas.** Son Stefánshellir, La Corona/Naturalistas, Rapa Nui y los salares de sulfato. Para subirlas faltan las coordenadas, la tarea y la fuente según el mínimo del inventario.
3. **No hay candidato terrestre para el Macizo Malapert,** cuya tarea es el enlace y la energía desde terreno elevado. Es la única de las cuatro referencias lunares sin sitio propuesto.
4. **PANGAEA está vinculada solo a «Polo sur lunar»** en las hipótesis del atlas, aunque su `planetIds` incluye Marte. Su uso en `neo.md` (Cueva de los Verdes) corresponde a Mare Tranquillitatis, y Caldera Blanca y Cueva de los Verdes son sectores distintos.
5. **Bhallil y Quinamávida no tienen geometría,** por lo que el filtro climático no les asigna celda.
6. **Ningún sitio tiene una dosis de radiación vinculada.** La radiación queda fuera de todos los análogos naturales y conviene decirlo de forma explícita en el pitch.
7. **Oportunidad:** Aucanquilcha A1 (sin permafrost) y Chajnantor B3 (con hielo) provienen del mismo estudio (Yoshikawa et al., 2025). Pueden presentarse como un **par de control** que sirve a la vez para Haworth y Arcadia.

---

## 7. Texto propuesto para el pitch

> Nuestros análogos no se eligen porque «se parecen» a la Luna o a Marte, sino por la **tarea** que permiten ensayar y por el **dato** que la respalda. En Pali-Aike, el Sol bajo de Magallanes sobre un cráter de paredes de 40–45° permite medir cuántos obstáculos pierde un rover con luz rasante antes de conducir en de Gerlache Rim 2. En Chajnantor, el sondeo B3 tiene un 46 % de hielo hasta 2 m, junto a sondeos sin permafrost. Ahí un rover puede practicar la primera decisión de una base en Haworth: dónde perforar para encontrar agua, y medir cuántas veces se equivoca. Para Marte, los lagos y salares andinos, como Miscanti y Pajonales, sirven para seleccionar muestras como en Jezero y para estudiar el agua contenida en minerales. Cada ficha dice también **dónde se rompe la analogía**: gravedad, vacío, radiación y frío criogénico se ensayan en instalaciones como LUNA, no en el campo. Así, científicos e ingenieros saben qué riesgo reduce cada lugar y qué queda por probar.
