# Prompt de trabajo: vista previa de la web de Coiponautas

Redactado el 14 de noviembre de 2026 con asistencia de IA (Claude, Anthropic), a partir del repositorio y del mapa XMind del equipo. El repo cambia rápido: quien use este archivo debe comprobar el estado actual antes de fiarse de lo que dice aquí.

## Cómo usar este archivo

- **Equipo:** completen "Responsable" y "Decisión" en los puntos de la sección [Por definir](#por-definir). Las decisiones se anotan aquí y no en los chats, para que todas las IAs partan de lo mismo.
- **Para avanzar un punto con tu IA:** comparte este archivo junto con el repo y dile qué punto quieres trabajar. Por ejemplo: "ayúdame a completar C2 con fuentes".
- **Para construir la web:** abre una sesión en la carpeta del repo y escribe: "Lee `prompt_web.md` y sigue la sección Encargo".

## Contexto

**Desafío.** NASA Space Apps Challenge 2026, [Identify Earth Locations that Analog the Permanent Moon Base Locations and Mars](https://www.spaceappschallenge.org/2026/challenges/permanent-moon-base-locations-and-mars/). Pide usar datos abiertos de la Tierra, la Luna y Marte para identificar y caracterizar lugares de la Tierra que sirvan de análogos, explicando en qué se parecen y dónde se rompe la analogía.

**Pregunta del equipo** (XMind): «¿Qué lugares terrestres menos utilizados podrían cubrir una necesidad específica de una misión análoga, y qué evidencia permite proponerlos?»

**Objetivo** (XMind): identificar y caracterizar sitios terrestres poco estudiados que cubran necesidades de exploración lunar o marciana, comparándolos con análogos conocidos. Tiene cuatro piezas:

- Usuario: quién necesita seleccionar el sitio.
- Actividad: qué quiere estudiar, probar o entrenar.
- Referencia planetaria: qué región o ambiente lunar o marciano desea representar.
- Resultado: candidatos justificados, limitaciones y evidencia pendiente.

**Idea** (XMind): una página web donde se ingresan los requerimientos de la misión y se muestran posibles localidades.

**Plazo.** La entrega cierra el domingo 15 de noviembre de 2026 a las 23:59, hora de Chile. Vale más algo simple que funcione que algo completo a medias.

## Dónde está cada cosa en el repo

Estado al 14 de noviembre, 21:00.

| Archivo | Autor | Contenido |
|---|---|---|
| [agente.md](agente.md) | Vicente | Contexto del equipo y tabla de los 11 recursos de datos del desafío |
| [Pancho.ipynb](Pancho.ipynb) | Pancho | Qué es un análogo, tipos, campo y laboratorio, qué necesita una base permanente |
| [figue.md](figue.md) | Figue | Luna: 6 instalaciones análogas, 5 zonas del polo sur, datos publicados de temperatura, iluminación y topografía |
| [matydrox.md](matydrox.md) | Matías | Marte: 4 regiones, 12 preguntas de ensayo (A1 a O3), 8 candidatos terrestres, verificación geográfica de 4, plantilla de ficha |
| [neo.md](neo.md) | Vicente | Cómo se evalúa un análogo, brechas, 4 regiones lunares con su tarea, piloto en Pali-Aike, qué mostrar en el prototipo |
| [luvsichexalogy.md](luvsichexalogy.md) | Joaco | 66 lugares análogos en uso y 8 programas, con quién los opera |
| [recopilación_datos.ipynb](recopilaci%C3%B3n_datos.ipynb) | Martín W. | Prueba de la API de NASA POWER en 4 puntos; gráfico sin terminar |
| `Estado del arte/` | Matías, Martín W., Figue | Dos documentos de Marte que repiten secciones de `matydrox.md`, y una carpeta con 3 PDF y 3 páginas de artículos |

Además:

- Los casos de estudio de Matías (Qaidam, PTAL, ARADS, PANGAEA y el marco de Stern) están solo en la rama `trabajo/matydrox`, en `Estado del arte/Analogos_planetarios_casos_de_estudio.md`.
- No hay ningún archivo de datos, código de la web ni imagen en ninguna rama.
- No existen `README.md`, `DATA_SOURCES.md` ni `AI_USAGE.md`.

## Encargo

Construye una **vista previa navegable** de la web: una versión que muestre cómo funcionaría, con los datos que ya existen en el repo y con cada punto sin resolver marcado a la vista. Sirve para que el equipo vea el flujo completo, decida lo que falta y tenga algo que mostrar. No es la versión final.

### Flujo de la web

Descrito por Pancho el 14 de noviembre. El equipo puede ajustarlo.

1. **Destino.** El usuario elige la Luna o Marte y un sitio. La página muestra también zonas sugeridas en ese cuerpo.
2. **Condiciones.** Se muestran las condiciones a las que está sometido el sitio elegido.
3. **Análogos actuales.** Lugares de la Tierra donde hoy se hacen misiones análogas: sus condiciones, por qué se usan, sus pros, su fidelidad y sus referencias.
4. **Prioridades.** El usuario indica qué relevancia tiene cada parámetro para su misión y elige el tipo de misión.
5. **Zonas.** Primero, las zonas que ya se usan hoy. Después, las zonas propuestas en el mundo: descripción, pros, contras, una imagen del terreno y enlaces para verla en Google Maps o Google Earth.

La intención es que sea interactiva y automática: un código cruza capas de datos de la Tierra (temperatura, relieve y otras) con los requerimientos y devuelve coordenadas. Ese código está en desarrollo (ver C5 y C6).

Otros integrantes ya escribieron qué esperan del prototipo: [neo.md](neo.md), sección "Qué mostrar en el prototipo", y [matydrox.md](matydrox.md), sección "Cómo se verá ante el jurado". Los dos piden que cada ficha separe dato medido, estimación e hipótesis, y que diga dónde se rompe la analogía, que además es un requisito del desafío. Inclúyelo en las fichas.

### Qué significa terminado

1. El flujo se recorre de principio a fin con al menos un sitio de la Luna y uno de Marte.
2. Todo dato visible tiene su fuente, o está marcado como pendiente o como ejemplo.
3. La página abre en un computador con Windows siguiendo las instrucciones que dejes escritas, y se puede publicar en un enlace público sin login.
4. Los datos están en archivos separados de la interfaz.

### Reglas

- **Plan primero.** Antes de crear archivos, muestra un plan corto (pantallas, archivos que vas a crear, qué queda por definir) y espera el visto bueno. El equipo quiere avanzar paso a paso.
- **No decidas lo que está por definir.** Según las reglas que maneja el equipo, en Space Apps una IA no puede idear la solución: la idea, los criterios, los pesos y los sitios los define el equipo. Si un punto de la lista te bloquea, pregunta o deja el marcador. No elijas tú.
- **No inventes datos.** Usa solo valores que estén en el repo con su fuente. Puedes completar un dato faltante si lo encuentras en una fuente citable: anota la fuente y márcalo como "added with AI, pending review". Si necesitas un valor de relleno para que algo se vea, márcalo como "example" en los datos y en la pantalla.
- **Lo pendiente se ve.** Cada punto por definir que afecte a una pantalla aparece en esa pantalla con su código, por ejemplo "To be defined · D2". Así nadie confunde la vista previa con un resultado.
- **Datos separados del código.** Los sitios, análogos, candidatos y parámetros van en archivos de datos que cada integrante pueda completar sin tocar la interfaz. Toma como base los campos de [matydrox.md](matydrox.md) ("Base estructurada que puede integrar el otro chat") y de [neo.md](neo.md) ("Ficha del prototipo"), y propón el formato en tu plan.
- **No toques lo que existe.** Crea solo los archivos de la web y sus datos. No muevas, renombres ni borres archivos: cada integrante trabaja en el suyo.
- **Todo lo que se entrega va en inglés:** interfaz, textos, comentarios y nombres de variables. Las notas del equipo están en español; tradúcelas al mostrarlas.
- **Sin marcas de la NASA.** No uses su logo ni insignias de misiones.
- **Declara el uso de IA.** Agrega una cabecera a cada archivo generado, por ejemplo `Portions of this file were generated with AI assistance (<herramienta>)`, y registra en `AI_USAGE.md` qué archivos creaste y para qué. Si ese archivo no existe, créalo.
- **Git.** No hagas commit ni push salvo que te lo pidan.
- **Comprueba antes de reportar.** Abre la página, recorre el flujo y di qué viste. Si algo falla o no lo pudiste probar, dilo.

### Qué devolver al terminar

- Los archivos que creaste y cómo abrir la página.
- Qué funciona y cómo lo comprobaste.
- Qué quedó como ejemplo o pendiente, y de qué punto (D o C) depende.
- Las preguntas que necesitas que el equipo responda.

## Por definir

Mientras un punto siga abierto, la vista previa hace lo que indica "Mientras tanto".

### Decisiones de método

**D1 · Cómo decide la web qué zonas mostrar**

- Por definir: si el resultado sale de (a) un cruce numérico de capas globales que devuelve las coordenadas más cercanas a lo pedido, (b) un catálogo de candidatos elegidos por el equipo, filtrado por tarea, donde cada criterio queda como cumple, descarta o pendiente, o (c) una combinación de las dos, y cuál.
- Insumos: para (a), [recopilación_datos.ipynb](recopilaci%C3%B3n_datos.ipynb). Para (b), [matydrox.md](matydrox.md), secciones "Regla común de comparación Tierra–Marte" y "Base estructurada…", y [neo.md](neo.md), sección "Qué mostrar en el prototipo".
- Mientras tanto: se muestran los candidatos que ya están en el repo, sin orden de mérito, y queda visible el espacio donde iría el resultado del cruce.
- Responsable: _sin asignar_
- Decisión: _pendiente_

**D2 · Regla para ponderar las prioridades**

- Por definir: cómo se convierten las prioridades del usuario en un resultado. Incluye la escala de entrada, la fórmula o las reglas, y qué hacer con condiciones que la Tierra no alcanza, como los 20 a 45 K del fondo de Haworth. Es el nodo vacío del XMind "¿Cómo se sopesan estas condiciones y a cuál darle prioridad?".
- Insumos: [matydrox.md](matydrox.md) pide no calcular un porcentaje único de parecido hasta definir tarea y pesos. [neo.md](neo.md) resume las métricas publicadas (ISO 10788, distancia euclidiana en Qaidam, índice SWIM, diez dimensiones en Isla Decepción).
- Mientras tanto: los controles de prioridad se muestran y guardan su valor, pero no cambian el resultado.
- Responsable: _sin asignar_
- Decisión: _pendiente_

**D3 · Parámetros que el usuario puede priorizar**

- Por definir: la lista final de parámetros, su unidad y cuáles tienen un dato real detrás.
- Insumos: las siete dimensiones del XMind: relieve; materiales, minerales y geología; ambiente, temperatura y radiación; agua, hielo y sales; actividad geológica, erupciones, cuevas y erosión; biología y biofirmas; uso del terreno (permisos, ubicación).
- Mientras tanto: se muestran esas siete dimensiones tal cual.
- Responsable: _sin asignar_
- Decisión: _pendiente_

**D4 · Tipos de misión**

- Por definir: la lista de tipos de misión o actividad que se puede elegir.
- Insumos: [neo.md](neo.md) propone cuatro ensayos: movilidad, muestreo geológico, operaciones con baja visibilidad y detección de recursos. [matydrox.md](matydrox.md) tiene doce preguntas de ensayo, de A1 a O3. [Pancho.ipynb](Pancho.ipynb) distingue ciencia, ingeniería y factores humanos.
- Mientras tanto: selector con los cuatro ensayos de `neo.md`, marcado como lista provisional.
- Responsable: _sin asignar_
- Decisión: _pendiente_

**D5 · Sitios de la Luna y Marte, y qué significa "zona óptima"**

- Por definir: si el usuario elige de una lista fija o puede ingresar coordenadas libres, qué sitios entran y con qué criterio se llama óptima a una zona.
- Insumos: [neo.md](neo.md) (de Gerlache Rim 2, Haworth, macizo Malapert, pozo de Mare Tranquillitatis), [figue.md](figue.md) (Connecting Ridge, Shackleton, de Gerlache, Malapert, Mons Mouton y las nueve regiones de la NASA de 2024) y [matydrox.md](matydrox.md) (Arcadia–Amazonis, Jezero, Gale, Oxia Planum). `figue.md` y `matydrox.md` aclaran que sus listas no son rankings oficiales.
- Mientras tanto: lista fija con los ocho sitios de `neo.md` y `matydrox.md`, presentados como "reference sites" y no como "optimal".
- Responsable: _sin asignar_
- Decisión: _pendiente_

**D6 · Cómo se expresa la fidelidad de un análogo**

- Por definir: la escala o el método (por dimensión, por tarea, cualitativa u otra) y quién la asigna.
- Insumos: el marco de Stern y colaboradores, en los casos de estudio de Matías (rama `trabajo/matydrox`); el puntaje de diez dimensiones de Isla Decepción citado en [neo.md](neo.md); los estados por propiedad de [matydrox.md](matydrox.md).
- Mientras tanto: cada ficha muestra "Fidelity: to be defined".
- Responsable: _sin asignar_
- Decisión: _pendiente_

**D7 · Tecnología y publicación**

- Por definir: página estática (HTML y JavaScript) o aplicación en Streamlit, y dónde se publica.
- Insumos: una página estática abre con doble clic y se puede publicar en GitHub Pages. Streamlit permite ejecutar en vivo el código Python del cruce, pero hay que instalarlo y publicarlo en un servicio aparte.
- Mientras tanto: página estática que abra con doble clic, sin servidor ni instalación. Ojo: los navegadores bloquean la lectura de archivos locales con `fetch`, así que los datos tienen que cargarse de otra forma.
- Responsable: _sin asignar_
- Decisión: _pendiente_

### Contenido y datos por completar

**C1 · Tabla de sitios de referencia (Luna y Marte)**

- Falta: las coordenadas de cada sitio y las mismas variables para todos. Hoy cada sitio tiene datos de puntos y métodos distintos. No hay pendiente ni elevación por sitio, ni temperatura local de Marte.
- Insumos: los valores publicados que ya están en [figue.md](figue.md), [neo.md](neo.md) y [matydrox.md](matydrox.md).
- Mientras tanto: ficha con los valores que ya están en esos archivos, cada uno con su fuente. Lo demás, "pending".
- Responsable: _sin asignar_

**C2 · Tabla de análogos en uso**

- Falta, por cada sitio: coordenadas, qué condiciones cubre, qué se ensaya (ciencia, hardware u operaciones humanas), quién lo opera, pros, contras y una fuente propia.
- Insumos: [luvsichexalogy.md](luvsichexalogy.md) (66 lugares y 8 programas, con referencias generales), [figue.md](figue.md) (6 instalaciones lunares con condiciones y fuente) y los comparadores de [matydrox.md](matydrox.md).
- Mientras tanto: se listan los sitios con los campos disponibles. Lo demás, "pending".
- Responsable: _sin asignar_

**C3 · Zonas propuestas**

- Falta: las coordenadas de 5 de los 9 candidatos (Bhallil, Chiprana, Aucanquilcha, Miscanti y Quinamávida), los pros y contras en formato de ficha, y más candidatos lunares (hoy solo está Pali-Aike).
- Insumos: [matydrox.md](matydrox.md), secciones "Lista corta mundial, ordenada por pregunta" y "Verificación geográfica y de datos de cuatro candidatos terrestres"; [neo.md](neo.md), sección "Aplicación al mapa web — piloto lunar en Pali-Aike".
- Mientras tanto: fichas con lo que ya está documentado. Los candidatos sin coordenadas no aparecen en el mapa y se listan aparte.
- Responsable: _sin asignar_

**C4 · Imágenes del terreno**

- Falta: no hay ninguna imagen en el repo. Hay que definir de dónde salen y revisar su licencia.
- Mientras tanto: recuadro "image pending" y enlaces a Google Maps y Google Earth generados desde las coordenadas. Comprueba que abren en el punto correcto.
- Responsable: _sin asignar_

**C5 · Capas de datos para el cruce**

- Falta: todas. Temperatura global en tierra: hay que volver a generarla (ver [Datos técnicos ya comprobados](#datos-técnicos-ya-comprobados)). Relieve y pendiente: nada descargado. Otras capas: sin definir.
- Insumos: [recopilación_datos.ipynb](recopilaci%C3%B3n_datos.ipynb) y la tabla de recursos de [agente.md](agente.md).
- Mientras tanto: la vista previa no hace ningún cruce.
- Responsable: _sin asignar_

**C6 · Conexión entre el código del cruce y la web**

- Por definir: qué recibe y qué devuelve el código del cruce (formato de entrada y de salida), para que la web pueda leerlo.
- Insumos: [recopilación_datos.ipynb](recopilaci%C3%B3n_datos.ipynb).
- Mientras tanto: la web deja preparado el lugar donde leería ese resultado.
- Responsable: _sin asignar_

## Datos técnicos ya comprobados

Probados el 14 de noviembre de 2026. Sirven para C5.

- **NASA POWER por punto.** `https://power.larc.nasa.gov/api/temporal/daily/point?parameters=T2M,T2M_MAX,T2M_MIN,TS&community=RE&longitude=<lon>&latitude=<lat>&start=20200101&end=20251231&format=CSV&header=false`. Devuelve un CSV sin login. Los datos faltantes vienen como -999.
- **NASA POWER global.** Hay un archivo Zarr público, sin login: `https://nasa-power.s3.us-west-2.amazonaws.com/merra2/spatial/power_merra2_monthly_spatial_utc.zarr`. Es mensual desde 1981, con una grilla de 0,5° de latitud por 0,625° de longitud (unos 50 km). Se abre con `xarray.open_zarr(url, consolidated=True)`. Los 72 meses de 2020 a 2025 con tres variables de temperatura bajan en unos 30 segundos y pesan 35 MB en NetCDF comprimido.
- **Variables de temperatura de POWER.** `T2M`, `T2M_MAX` y `T2M_MIN` son la temperatura del aire a 2 m. `TS` es la temperatura de la superficie. Todas en °C.
- **Máscara de tierra.** El paquete `global-land-mask` separa tierra y océano y conserva la Antártica y Groenlandia. Las variables de POWER que solo existen en tierra, como `TSOIL1`, dejan fuera las capas de hielo, así que no sirven como máscara.
- **Resolución.** La grilla de POWER sirve para el clima regional. No distingue un cráter o un salar pequeño de su entorno.
- **CDAWeb no sirve para esto.** Es un portal de heliofísica: no tiene temperatura de la superficie terrestre.

## Requisitos de la entrega que todavía no existen

- `README.md` en inglés: qué hace, cómo correrlo, resultados, límites de la analogía y créditos de datos.
- Un entregable funcionando con enlace público, sin login.
- `DATA_SOURCES.md` con cada fuente usada. Al menos una tiene que ser de la NASA.
- `AI_USAGE.md` con todo lo generado con IA, incluidos los documentos de investigación.
- Demo: máximo 7 diapositivas o un video de hasta 30 segundos, en inglés.
