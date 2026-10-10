# Global Trade Comparative Analysis

Mismo dataset, tres herramientas: comparativo de Tableau Public, Looker Studio y RawGraphs + Figma.

**Datos:** Banco Mundial (WDI), 15 países, 2015-2024, 4 indicadores
(Exportaciones, Importaciones, Comercio % del PIB, PIB per cápita).

## Entregables
- Tableau Public: https://public.tableau.com/app/profile/jason.martinez.castro/viz/GlobalTradeComparativeAnalysis/Comercioexterior
- Looker Studio: https://datastudio.google.com/reporting/53b4999a-82ac-4fba-a116-82e258c7346b
- Pieza editorial (RawGraphs + Figma): rawgraphs_figma/comercio_2024_final.png

## Hallazgo principal
Colombia ocupa el puesto 12 de 15 en apertura comercial 2024 (36,3 % del PIB).
Corea del Sur (84,6 %) y Alemania (79,1 %) lideran.

## Comparativo
| Criterio | Tableau | Looker Studio | RawGraphs + Figma |
|---|---|---|---|
| Interactividad | Alta | Media | Estática |
| Rapidez | Media | Alta | Media |
| Control de diseño | Alto | Limitado | Total |
| Mejor uso | Análisis | Reportes | Storytelling |

## Notas técnicas
- La columna Value mezcla unidades: nunca se agrega entre indicadores.
- Looker Studio no tiene títulos dinámicos; Tableau sí.
- El .twb apunta a la ruta local del CSV.

## Estructura
data_raw/ · tableau/ · outputs/ · rawgraphs_figma/ · docs/ · looker/