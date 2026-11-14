# Arcadia–Amazonis: consolidación de evidencia para la búsqueda de análogos terrestres

**Proyecto:** NASA Space Apps Challenge 2026  
**Línea de investigación:** Marte — Matías  
**Fecha:** 14 de noviembre de 2026  
**Estado:** revisión documental e inspección inicial de datos; pendiente de revisión del equipo  
**Ruta en el repositorio:** `Estado del arte/Arcadia_Amazonis_consolidacion_de_evidencia.md`

## 1. Propósito y relación con el documento anterior

Este documento recopila lo avanzado desde `Investigacion_Marte_requisitos_para_analogos.md`: la elección exploratoria de Arcadia–Amazonis, la revisión de los archivos aportados, los datos disponibles para AP-1, AP-8 y AP-9, las incertidumbres detectadas y la corrección del enfoque de trabajo.

El objetivo sigue siendo **caracterizar sitios marcianos para buscar análogos terrestres**. Evaluar el hielo, el aterrizaje o la extracción de recursos son partes posibles de esa caracterización, no objetivos que sustituyan automáticamente el desafío.

El documento anterior planteó dos líneas iniciales —hielo y operaciones en Arcadia–Amazonis; materiales y búsqueda de señales en Oxia/Jezero—. Se comenzó por Arcadia–Amazonis para examinar información concreta. Esta elección fue exploratoria: no surgió de un ranking cuantitativo de todas las regiones de Marte.

**Límite de esta entrega:** consolida lo aprendido. La siguiente etapa será interpretar conjuntamente esta evidencia para decidir qué características buscar y exigir a los candidatos terrestres. Esa selección de requisitos y la búsqueda de nuevos sitios no se desarrollan aquí.

## 2. Enfoque acordado

La secuencia de trabajo queda definida así:

1. Identificar y delimitar referencias marcianas.
2. Recopilar sus características y fuentes, conservando escalas e incertidumbres.
3. Determinar, en una etapa posterior, qué propiedades son relevantes para distintas actividades análogas.
4. Buscar y caracterizar candidatos terrestres con evidencia comparable.
5. Presentar las correspondencias y diferencias en un catálogo visual filtrable según el objetivo de la misión análoga.

No se exige que un lugar terrestre reproduzca todo Marte. La utilidad de una analogía dependerá de la actividad y de las propiedades que efectivamente represente. La originalidad de un sitio poco estudiado debe acompañarse de evidencia suficiente.

## 3. Material revisado

| Fuente aportada | Contenido revisado | Función |
|---|---|---|
| Luzzi et al., 2025 | Artículo de 38 páginas; tablas, métodos y resultados de AP-1/AP-8/AP-9 | Referencia principal para los sitios marcianos |
| Anglés y Li, 2017 | Artículo de 33 páginas; localizaciones comparadas, campaña y mineralogía | Antecedente terrestre de Qaidam |
| `MARTE 2026 .docx` | Notas sobre Arcadia y texto de divulgación de NASA sobre SWIM | Síntesis inicial, contrastada con los artículos |
| `SWIMProducts.zip` | Cuatro ZIP internos, README, 27 GeoTIFF y componentes de un shapefile | Inspección de datos geográficos auxiliares |

La revisión incluyó extracción de texto de ambos artículos, inspección visual de tablas relevantes, lectura de las notas y descompresión de los paquetes SWIM. Se inspeccionaron valores y metadatos de las diez capas de la carpeta 0–1 m, se compararon sus archivos correspondientes con la carpeta 1–5 m y se extrajeron valores puntuales en las coordenadas publicadas de los tres sitios.

Los datos de los artículos no se recalcularon desde las imágenes originales. Las extracciones puntuales de SWIM sí se realizaron sobre los archivos entregados. No se ejecutó una comparación nueva Marte–Tierra.

## 4. Unidad geográfica de análisis

La región general es **Arcadia–Amazonis**, y las referencias locales son **AP-1, AP-8 y AP-9**, situadas en el límite entre Amazonis septentrional y Arcadia Planitia.

El artículo distingue el punto del sitio de aterrizaje del área circundante. Sus mapas geomorfológicos abarcan las huellas de imágenes HiRISE; no deben tratarse como elipses de aterrizaje ni como polígonos del mismo tamaño. [L, pp. 5–6]

| Sitio | Latitud | Longitud este 0–360° | Longitud equivalente −180–180° |
|---|---:|---:|---:|
| AP-1 | 39,8° N | 202,1° E | −157,9° |
| AP-8 | 40,75° N | 201,3° E | −158,7° |
| AP-9 | 40,02° N | 203,35° E | −156,65° |

La última columna es una conversión aritmética para facilitar usos cartográficos. No cambia el cuerpo planetario ni convierte las coordenadas en coordenadas terrestres.

## 5. Caracterización documentada de los tres sitios

### 5.1 Relieve, polígonos e indicadores

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

### 5.2 Microrelieve de polígonos

El artículo distingue polígonos de centro elevado suave y polígonos de centro elevado con montículo. En una submuestra de 35 de cada tipo por región —105 por tipo en total—, los segundos presentan alturas típicas de 0,5–1,6 m, moda de 0,8 m y desviación estándar de 0,25 m. Los de centro elevado suave no superan 0,4 m, con moda de 0,2 m y desviación estándar de 0,1 m. [L, p. 15]

Estas estadísticas se reportan para el conjunto muestreado, no como distribuciones independientes completas de cada sitio. La precisión vertical de los modelos es del orden de decenas de centímetros, por lo que las alturas menores presentan incertidumbre considerable.

El diámetro modal es el valor más frecuente de la distribución estimada; no debe rotularse como diámetro medio. La desviación estándar describe dispersión, no incertidumbre instrumental.

## 6. Hielo: separar observación, inferencia y contexto

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

## 7. Valores SWIM publicados en el artículo

| Sitio | Combinado 0–1 m | Geomorfología | Neutrones | Potencia radar superficial | Térmico | Propiedades dieléctricas estimadas |
|---|---:|---:|---:|---:|---:|---:|
| AP-1 | 0,20 | 0,63 | 0,29 | 0 | 0 | 0,10 |
| AP-8 | 0,39 | 0,75 | 0,51 | 0 | 0,33 | 0,39 |
| AP-9 | 0,43 | 0,75 | 0,51 | 0 | 0,33 | 0,55 |
| Cráter con exposición de hielo | 0,30 | 0,75 | 0,29 | 0,50 | 0 | 0 |

Transcripción de la tabla 3, página 19. [L]

Son índices de consistencia de evidencias. **0,43 no equivale a 43 % de probabilidad, 43 % de hielo ni una profundidad.** No se recalcularon con el ZIP aportado.

Los autores destacan que el cráter con hielo expuesto tiene un índice combinado menor que AP-8 y AP-9. Esto ilustra límites de una evaluación regional cuando se interpreta localmente. No invalida toda la cartografía ni permite corregir índices sin un método documentado.

## 8. Inventario e inspección del paquete SWIM

### 8.1 Contenido

| Paquete interno | Contenido |
|---|---|
| `SWIM4MIM_G_0_1_Ancillary.zip` | 10 capas geomorfológicas auxiliares y README |
| `SWIM4MIM_G_1_5_Ancillary.zip` | 10 capas geomorfológicas auxiliares y README |
| `SWIM4MIM_G_5_Ancillary.zip` | 7 capas geomorfológicas auxiliares y README |
| `SWIM4MIM_RZ_Ancillary.zip` | Geometría de zonas de reconocimiento y README |

Las capas representan cráteres expandidos, rellenos, depósitos glaciares, manto dependiente de latitud, cráteres pedestal, polígonos, cráteres de molde anular, terreno festoneado, cráteres aterrazados y terreno texturado. Los nombres deben conservarse junto a los originales para evitar ambigüedad. [S]

### 8.2 Propiedades verificadas

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

### 8.3 Ponderaciones y significado de los intervalos

Los README asignan pesos diferentes a algunas de las mismas capas según el intervalo. Por ejemplo, los depósitos glaciares pasan de 0,75 en 0–1 m a 1 en 1–5 m; los polígonos pasan de 1 a 0,5. [S]

Por tanto, no son dos observaciones independientes que midan físicamente la profundidad del hielo: son datos auxiliares compartidos para una interpretación por intervalos. El README de 1–5 m contiene además una referencia textual a «1-0m», inconsistente con el nombre del paquete; no se corrigió el original.

### 8.4 Hallazgos de calidad

- La capa de polígonos contiene valores próximos a **−3,4 × 10³⁸**, además del NoData declarado de −30. Deben aclararse y tratarse explícitamente antes de calcular estadísticas.
- Esa capa también presenta algunos valores superiores a 1. No se debe asumir sin documentación que sea una probabilidad o una máscara binaria.
- Las demás capas 0–1 m inspeccionadas contienen valores 0 y 1. Su interpretación física debe seguir el método de la fuente; un cero no equivale a ausencia de hielo.
- No se incluyeron mapas combinados ni todas las capas térmicas, de neutrones y radar de la tabla de Luzzi.
- No se aplicaron correcciones a los archivos originales ni se calculó un índice combinado nuevo.

### 8.5 Extracciones puntuales realizadas

Se transformaron las coordenadas de los sitios al sistema de los raster y se leyó el píxel correspondiente en las capas 0–1 m. Los siguientes son valores auxiliares originales:

| Capa | AP-1 | AP-8 | AP-9 |
|---|---:|---:|---:|
| Cráteres expandidos | 1 | 1 | 1 |
| Manto dependiente de latitud | 1 | 1 | 1 |
| Terreno texturado | 1 | 1 | 1 |
| Terreno festoneado | 0 | 0 | 1 |
| Cráteres aterrazados | 0 | 1 | 0 |

Son descriptores de píxeles regionales; no porcentajes de cobertura del sitio ni inventarios de todas las formas presentes. No deben confundirse con las mediciones y valores SWIM publicados en el artículo.

## 9. Qaidam: evidencia terrestre ya reunida

El artículo de Anglés y Li documenta sectores del oeste de Qaidam y los compara con estructuras marcianas. Es un antecedente útil para nuestro catálogo, pero no demuestra una analogía integral con Arcadia. [Q]

### 9.1 Sectores identificados

| Coordenadas terrestres de un ejemplo | Característica documentada |
|---|---|
| 38,75° N; 91,75° E | Terrenos poligonales |
| 38,32° N; 91,27° E | Cárcavas |
| 39,16° N; 92,00° E | Valles fluviales y abanicos aluviales |
| 37,61° N; 92,23° E | Yardangs |
| 38,37° N; 91,63° E | Campos de dunas |
| 38,49° N; 91,74° E | Estructuras anulares |

Fuente: tabla 1, página 3 del PDF, página impresa 858. Son localizaciones de ejemplos ilustrados, no límites completos de sitios de prueba.

### 9.2 Campaña y materiales

La investigación describe una expedición de diez días en agosto de 2016, nueve localidades y 78 muestras. Incluye microscopía electrónica, difracción de rayos X y análisis termogravimétrico de tres muestras de yeso. Documenta halita, yeso y otros minerales, con limitaciones en la identificación de fases menores. [Q, secciones 3.1–3.2]

Las propiedades de una muestra no deben atribuirse automáticamente a todos los sectores de la tabla. El parecido geométrico de polígonos tampoco establece que tengan el mismo proceso de formación o hielo subsuperficial comparable.

**Estado para el proyecto:** referencia terrestre documentada por sectores y dimensiones; no seleccionado como análogo integral de AP-1, AP-8 o AP-9.

## 10. Correcciones a la síntesis inicial

| Afirmación inicial o riesgo de interpretación | Formulación que conservaremos |
|---|---|
| «Se filtraron cuatro regiones de Marte» | Se eligieron exploratoriamente cuatro referencias; no hubo filtro cuantitativo global |
| «Arcadia es plana» | Hay sectores de bajo relieve; la variabilidad y escala deben especificarse |
| «Hielo a 10 cm» | Estimación indirecta asociada al patrón poligonal y su formación, no profundidad actual confirmada |
| «Hielo a 50–60 cm en AP-1» | Exposición en un cráter situado aproximadamente a 23 km, medida respecto a su borde |
| «Depósitos de 30–80 m» | Cifra de las notas pendiente de fuente y delimitación; no se asigna a los tres sitios |
| «SWIM 0,43 = 43 %» | Índice de consistencia; no probabilidad, pureza o profundidad |
| «Capas de 0–1 y 1–5 m son mediciones distintas» | Los pares de raster son idénticos y cambian algunas ponderaciones documentadas |
| «Qaidam reproduce Arcadia» | Hay comparaciones posibles por dimensión; aún no una correspondencia integral demostrada |
| «Sitio favorable para aterrizar = sitio validado» | Se trata de candidatos evaluados bajo criterios y escalas de estudios concretos |

Las notas `MARTE 2026 .docx` se conservan como síntesis de trabajo; los artículos y productos identificados respaldan los campos técnicos. [N]

## 11. Estado de la caracterización y vacíos

| Dimensión | Evidencia disponible | Limitación pendiente |
|---|---|---|
| Ubicación | Coordenadas de los tres sitios | Definir polígonos operativos de comparación |
| Relieve | Desniveles e imágenes/modelos identificados | Comparación sobre áreas y escalas homogéneas |
| Morfología | Inventarios y tamaños de polígonos | Recuperar cartografía digital y su cobertura |
| Hielo | Indicios, modelos y exposición cercana | Profundidad y continuidad actuales por sitio |
| Materiales | Contexto regional | Composición y granulometría local suficientes |
| Ambiente térmico | Contexto general | Valores específicos con período y escala |
| Polvo y viento | Contexto general | Caracterización local útil para una actividad definida |
| Propiedades mecánicas | Información insuficiente en lo revisado | Resistencia, cohesión y comportamiento del subsuelo |
| Radiación y presión | Contexto planetario | Definir su relevancia para las actividades análogas |

Los datos faltantes permanecen como desconocidos. No se sustituirán por promedios de Marte presentados como mediciones de AP-1/AP-8/AP-9.

## 12. Productos identificados para continuar después

### 12.1 Imágenes y pares estéreo del artículo

| Sitio | Imagen principal | Par estéreo |
|---|---|---|
| AP-1 | `ESP_052490_2200` | `ESP_052424_2200` |
| AP-8 | `ESP_043220_2210` | `ESP_042930_2210` |
| AP-9 | `ESP_060811_2205` | `ESP_060323_2205` |

La tabla 1 de Luzzi indica 25 cm/píxel para las imágenes proyectadas; la escala original de estos pares ronda 30–32 cm/píxel. El remuestreo no crea detalle nuevo. No confundir escala de imagen con resolución horizontal del modelo de elevación o precisión vertical. [L, p. 6]

### 12.2 Cartografía vectorial

El artículo enlaza el conjunto **Geomorphic maps of candidate landing sites in northern Amazonis Planitia**, Luzzi, Nodjoumi y Heldmann (2024), DOI [10.5281/zenodo.13647425](https://doi.org/10.5281/zenodo.13647425).

Este conjunto fue identificado en la bibliografía, pero no se descargó ni inspeccionó en la revisión consolidada aquí. Las imágenes originales pueden localizarse mediante [PDS Orbital Data Explorer](https://ode.rsl.wustl.edu/).

## 13. Punto de cierre y siguiente etapa

Quedan consolidadas tres sitios de referencia marcianos de una misma región, varios sectores terrestres documentados de Qaidam y un inventario de las capas auxiliares SWIM disponibles.

**Siguiente etapa:** definir qué buscar en la Tierra y qué requisitos exigir según el objetivo de la misión análoga. No se decide aquí una lista final de requisitos, ponderaciones, candidatos nuevos ni un ranking.

Para reproducir las extracciones de SWIM, queda pendiente registrar la versión o suma de verificación del ZIP, los nombres exactos de las capas, la transformación de coordenadas y el tratamiento de NoData. Las comprobaciones del paquete se conservan como resultados reportados en el borrador; quedan pendientes de reproducción por el equipo.

## 14. Fuentes y trazabilidad

- **[L] Luzzi et al. (2025).** *Geomorphological Evidence of Near-Surface Ice at Candidate Landing Sites in Northern Amazonis Planitia, Mars*. [DOI](https://doi.org/10.1029/2024JE008724). Las páginas citadas corresponden a las 38 páginas del PDF.
- **[Q] Anglés, A. y Li, Y. (2017).** *The western Qaidam Basin as a potential Martian environmental analogue: An overview*. [DOI](https://doi.org/10.1002/2017JE005293).
- **[S] Paquete SWIM aportado.** `SWIMProducts.zip`. Los README solicitan citar Morgan, G. A., Putzig, N. E. y colaboradores (2025), *Refined Mapping of Subsurface Water Ice on Mars to Support Future Missions*, Planetary Science Journal, 6, 29, [DOI](https://doi.org/10.3847/PSJ/ad9b24). El inventario y las comprobaciones descritas proceden de los archivos aportados; no implican revisión completa de ese artículo metodológico.
- **[N] Notas de trabajo.** `MARTE 2026 .docx` (archivo de trabajo del equipo).
- **Contexto previo.** [NASA, 26 de octubre de 2023: cartografía del hielo marciano](https://www.nasa.gov/solar-system/planets/mars/nasa-is-locating-ice-on-mars-with-this-new-map/) y [portal SWIM](https://swim.psi.edu/).
- **Documento anterior.** [Investigacion_Marte_requisitos_para_analogos.md](Investigacion_Marte_requisitos_para_analogos.md).
