# Cambios del atlas · versión v1_pancho

**Coiponautas · NASA Space Apps Challenge 2026 · 15 de noviembre de 2026**

Este documento describe los cambios de [`Coiponautas-Atlas-Interactivo-v1_pancho.html`](Coiponautas-Atlas-Interactivo-v1_pancho.html) respecto de la versión del atlas en la que se basaron, y explica cómo juntarlos con la versión actual de `Coiponautas-Atlas-Interactivo.html`.

## 1. Resumen

| | |
| --- | --- |
| **Archivo nuevo** | `Coiponautas-Atlas-Interactivo-v1_pancho.html` |
| **Versión base** | `Coiponautas-Atlas-Interactivo.html` del commit [`81323e6`](https://github.com/MartinWilckens/Coiponautas/commit/81323e6) («Integra radiación de onda corta y larga de NASA POWER») |
| **Archivo original** | `Coiponautas-Atlas-Interactivo.html` **no se modificó** en este commit. Sigue siendo la versión del equipo. |
| **Forma del cambio** | Un solo bloque nuevo de 637 líneas (CSS + JavaScript), insertado justo antes de `<script>const yammaGeometry`. **No se cambió ni se borró ninguna línea del original.** Fuera del bloque, la única diferencia son dos saltos de línea. |
| **Delimitadores del bloque** | Empieza en `<!-- ===== Módulo Coiponautas: zonas de misión en la Luna y Marte ===== -->` y termina en `<!-- ===== Fin del módulo de zonas de misión ===== -->`. |
| **Prueba de fusión** | El bloque se insertó en la versión del commit [`aa443a0`](https://github.com/MartinWilckens/Coiponautas/commit/aa443a0) («Recalcula el candidato destacado al ajustar la misión») y funcionó sin errores (sección 3). |

## 2. Qué cambia para quien usa el atlas

### 2.1 Zonas de misión en la Luna y Marte

- **Ocho zonas de referencia.** Cuatro lunares: L1 de Gerlache Rim 2, L2 Haworth, L3 Macizo Malapert y L4 pozo de Mare Tranquillitatis. Cuatro marcianas: M1 Arcadia–Amazonis (AP-1), M2 Jezero, M3 Gale y M4 Oxia Planum.
- **Contenido de cada zona:**
  - coordenadas;
  - ensayo que orienta la búsqueda;
  - cuatro condiciones documentadas;
  - «¿Por qué importa?»;
  - análogos terrestres de referencia;
  - fuentes con enlace;
  - foto de dominio público.
- **Origen de los datos:** `neo.md` (Luna) y `matydrox.md` (Marte). La tabla de la sección 4 detalla cada zona.

### 2.2 Mapa de la Luna y de Marte, aparte del de la Tierra

- **Selector de mapa:** debajo de «Destino» hay un selector nuevo, **Mapa: 🌍 Tierra · 🌕 Luna · 🔴 Marte**. Es independiente del destino.
- **Mapa planetario:** al elegir Luna o Marte se abre un mapa propio que tapa por completo el terrestre. Muestra solo ese cuerpo y sus zonas, sin sitios ni capas de la Tierra.
- **Mosaicos:** son de NASA Trek (LRO WAC para la Luna, Viking MDIM 2.1 para Marte), en proyección equirectangular. Las zonas polares aparecen en su latitud real; no se recortan a −84° como en Web Mercator.
- **Ficha lateral:** al hacer clic en una zona se abre una ficha al costado, con el mismo estilo que la de los sitios terrestres. Al pulsar un análogo de referencia, se vuelve al mapa de la Tierra y se abre su ficha.
- **Barra plegable:** la barra superior del mapa planetario se pliega con ▴/▾.

### 2.3 Destino y ejemplos de búsqueda

- **Destino sin cambios:** **Todos / Luna / Marte** siguen funcionando como antes. Solo filtran los análogos en la Tierra y no cambian el mapa.
- **Panel de zonas:** con Luna o Marte elegido aparece el panel «Zonas de misión», con «Ver en el mapa» y «Buscar análogos en la Tierra».
- **Ejemplos de búsqueda por zona de misión:** cada ejemplo carga en el perfil del atlas el destino, las tareas y los criterios. Los criterios se cargan **como preferencias («Priorizar»)**, así que no excluyen sitios sin datos.

### 2.4 Panel lateral más compacto

- **Secciones plegables:** se pliegan con ▾/▸ o pulsando el título. Son ocho: Destino, Mapa, Zonas de misión, Qué quieres probar, Ejemplos de búsqueda, Qué debe tener el sitio, Capas ambientales y Resultados. «Ejemplos de búsqueda» y «Capas ambientales» empiezan plegadas.
- **Resumen de cada sección plegada:** un recuadro con el nombre en negrita, centrado, y **solo los filtros activos** como etiquetas. La **✕** quita el filtro sin desplegar la sección. Las etiquetas de criterios y de capas reutilizan los botones del atlas (`data-remove`, `data-clear-climate`).
- **Panel completo plegable:** una pestaña ◀/▶ en el borde izquierdo del mapa pliega todo el panel hacia el lado. Solo en pantallas de más de 760 px.
- **Barra superior plegable:** una pestaña ▲/▼ bajo la barra superior la oculta, y el mapa gana todo el alto.
- **Controles del mapa terrestre:** «▴ Ocultar controles» pliega la fila de botones del mapa de la Tierra.
- **Estado recordado:** el atlas recuerda en el navegador lo que cada persona dejó plegado (clave `coipo-folds` de `localStorage`). Si el navegador no permite guardar, el atlas funciona igual.

### 2.5 Otros

- **Traducción:** todos los textos nuevos se traducen al inglés con el selector de idioma del atlas. El módulo agrega sus frases al diccionario `english` del atlas.
- **Copia HTML:** «Guardar copia HTML» incluye el módulo. El bloque está antes del script principal, así que queda dentro de `originalHTML`.

## 3. Cómo juntar esta versión con la del equipo

Como el cambio es un bloque autocontenido, no hace falta fusionar línea por línea.

1. Abrir `Coiponautas-Atlas-Interactivo-v1_pancho.html` y copiar **desde** `<!-- ===== Módulo Coiponautas: zonas de misión en la Luna y Marte ===== -->` **hasta** `<!-- ===== Fin del módulo de zonas de misión ===== -->`, ambos incluidos.
2. En `Coiponautas-Atlas-Interactivo.html`, la versión más nueva del equipo, pegarlo justo antes de `<script>const yammaGeometry`. Ese texto aparece una sola vez.
3. Abrir el atlas y probar: Mapa → Luna, clic en una zona, «Buscar análogos en la Tierra», plegar secciones y cambiar a inglés.
4. Cuando la versión unida funcione, se puede borrar `-v1_pancho.html`.

**Prueba ya hecha sobre `aa443a0`.** En una copia temporal se insertó el bloque en la versión de `aa443a0` y se comprobó lo siguiente:

- carga el panel de zonas, el selector de mapa, las 8 secciones plegables y las pestañas del panel y de la barra superior;
- Mapa → Marte abre el mapa marciano, y clic en Jezero abre su ficha;
- «Buscar análogos» carga cuatro criterios como preferencias y vuelve a la Tierra. Los primeros resultados fueron Laguna Miscanti, Salada de Chiprana, Salar de Pajonales y Williams Point;
- los resúmenes plegados muestran los filtros activos;
- «Guardar copia HTML» conserva el módulo;
- la consola no muestra errores.

**Qué podría romper la fusión.** El módulo depende de estas partes del atlas. Si alguien las renombra, hay que ajustar el bloque:

| Tipo | Nombres que usa el módulo |
| --- | --- |
| Variables y funciones globales | `profile`, `sync()`, `render()`, `reset()`, `map`, `catalog`, `properties`, `taskNames`, `english`, `escapeHTML`, `q`, `activeClimateRanges`, `climateVariables`, `formatClimate`, `onlySaved`, `zone`, `monitorImages`, `showMap`, `originalHTML` |
| Elementos de la página | `.destination-filter`, `[data-destination]`, `#task-picker`, `.mission-panel`, `.criteria-heading`, `.climate-panel`, `#climate-title`, `#candidate-results`, `#count`, `#search`, `#reset`, `#clear-area`, `#map`, `#map-panel`, `.map-tools`, `#quick-criteria`, `#sidebar`, `body > header`, `#atlas-language` |
| Identificadores de sitios | `pali-aike`, `chajnantor-b3`, `aucanquilcha`, `luna`, `saskylakh`, `yamma`, `miscanti`, `williams`, `chiprana`, `bhallil`, `quinamavida`, `joaco-14`, `joaco-16`, `joaco-18`, `joaco-19`, `joaco-26`, `joaco-27`, `joaco-35`, `joaco-43`, `joaco-44`, `joaco-63` |

Todos existen en `aa443a0`.

## 4. Datos de las zonas de misión

| Código | Zona | Lat, lon | Ensayo | Fuentes principales |
| --- | --- | --- | --- | --- |
| L1 | de Gerlache Rim 2 | −88,45°, −67,86° (punto dGR2_K2023) | Movilidad con Sol rasante | [Wueller et al. 2026](https://doi.org/10.1029/2025JE009434), [Williams et al. 2019](https://doi.org/10.1029/2019JE006028), `neo.md` |
| L2 | Haworth | −86,9°, −4,0° (centro del cráter) | Prospección de hielo | [Williams et al. 2019](https://doi.org/10.1029/2019JE006028), [Li et al. 2018](https://doi.org/10.1073/pnas.1802345115), [Colaprete et al. 2010](https://doi.org/10.1126/science.1186986) |
| L3 | Macizo Malapert | −85,964°, −2,319° (aterrizaje hipotético) | Repetidor de comunicaciones y energía | [Estudio de rutas, 2024](https://doi.org/10.1029/2024JE008905), [NASA PGDA](https://pgda.gsfc.nasa.gov/products/78) |
| L4 | Pozo de Mare Tranquillitatis | 8,3355°, 33,222° | Cartografía de cavidades | [NASA](https://science.nasa.gov/photojournal/new-views-of-lunar-pits/), [Carrer et al. 2024](https://doi.org/10.1038/s41550-024-02302-y), [Horvath et al. 2022](https://doi.org/10.1029/2022GL099710) |
| M1 | Arcadia–Amazonis (AP-1) | 39,8°, −157,9° | Detección y perforación de hielo | [Luzzi et al. 2025](https://doi.org/10.1029/2024JE008724), `matydrox.md` |
| M2 | Jezero | 18,38°, 77,58° | Muestreo en un delta y biofirmas | [NASA Mars 2020](https://science.nasa.gov/mission/mars-2020-perseverance/), `matydrox.md` |
| M3 | Gale | −5,4°, 137,8° | Estratigrafía, sales y perforación | [NASA MSL](https://science.nasa.gov/mission/msl-curiosity/), `matydrox.md` |
| M4 | Oxia Planum | 18,275°, −24,632° | Perforación en arcillas | [ESA ExoMars](https://www.esa.int/Science_Exploration/Human_and_Robotic_Exploration/Exploration/ExoMars), `matydrox.md` |

**Correcciones respecto del paquete ZIP de otra IA** (`Coiponautas_Atlas_Planetary_Package.zip`), que fue el punto de partida del módulo:

- **Arcadia:** se usa AP-1 de `matydrox.md` (39,8° N, −157,9°) en lugar de 39,5° N, −172°.
- **LCROSS:** el 5,6 ± 2,9 % de hielo corresponde a **Cabeus**, no a Haworth, como indica `neo.md`.
- **Valores sin fuente eliminados:** las temperaturas medias de Jezero, Gale, Oxia y Arcadia, la prominencia de Malapert y la elevación «−3.000 m» de Oxia. `matydrox.md` pide no usar un valor único sin indicar hora, estación y lugar.
- **Criterios de búsqueda sin sentido eliminados:** la altitud terrestre como análogo de Malapert, el espesor de cobertura en Gale y Oxia, y el valor de cuevas restringido a «Cueva de El Escalón».
- **Implementación:** el ZIP superponía el mapa planetario al terrestre y dejaba las zonas polares en −84°. Además, marcaba todos los criterios como obligatorios y perdía el módulo al guardar la copia HTML. Todo eso quedó corregido.

**Fotos (Wikimedia Commons, todas de dominio público).** Se cargan desde `Special:FilePath`:

| Zona | Archivo |
| --- | --- |
| L1 | `DeGerlacheCrater.jpg` |
| L2 | `Lunar south pole summer annotated.jpg` (contexto del polo) |
| L3 | `463785main malapertregion 500.jpg` |
| L4 | `Mare Tranquillitatis pit crater.jpg` |
| M1 | `Arcadia Planitia.jpg` (contexto regional) |
| M2 | `Spanning the Delta of Jezero Crater on Mars (PIA25022).jpg` |
| M3 | `MarsCuriosityRover-MountSharp-Sol 1100.jpg` |
| M4 | `Oxia Planum near Coogoon Vallis by HiRise.jpg` |

## 5. Recursos externos

- **Mosaico lunar:** `https://trek.nasa.gov/tiles/Moon/EQ/LRO_WAC_Mosaic_Global_303ppd_v02/1.0.0/default/default028mm/{z}/{y}/{x}.jpg`, hasta el nivel 8.
- **Mosaico marciano:** `https://trek.nasa.gov/tiles/Mars/EQ/Mars_Viking_MDIM21_ClrMosaic_global_232m/1.0.0/default/default028mm/{z}/{y}/{x}.jpg`, hasta el nivel 7.
- **Fotos:** `commons.wikimedia.org/wiki/Special:FilePath/…`.

Sin internet, el mapa planetario y las fotos no cargan; el resto del atlas funciona igual.

## 6. Limitaciones conocidas

- A escala global, Haworth (L2) y Malapert (L3) casi se superponen porque están a menos de 2° entre sí. Con «Ver en el mapa» o el zoom se separan.
- La proyección equirectangular deforma en horizontal cerca de los polos.
- Los textos de las zonas están en español e inglés, pero los nombres de los sitios terrestres siguen el idioma de cada ficha del catálogo.
- Las fotos de L2 y M1 son de contexto regional, no del sitio exacto.
