---
title: El Código
layout: template
filename: cami-codigo.md
---

## Hablemos de código

Nuestras metas se basan en los objetivos planteados por **MakeSens**:

Un algoritmo que organice los cultivos a partir de históricos ambientales, ubicando en primer lugar, el cultivo que podría prosperar en condiciones óptimas (Según el histórico de datos) y el que peor prosperará.

Filtraje inicial por temperatura: si la temperatura se sale de los extremos viables para un cultivo, entonces se descarta (Temperatura promedio en cierto intervalo de tiempo considerando una desviación estándar).
Determinación de relevancia para los parámetros de precipitación acumulada y de humedad promedio.
Considerar la cercanía a los valores óptimos en caso de empate.
Clasificar de acuerdo probabilidad de éxito.
Considerar los costos y tiempos de producción para clasificar de acuerdo a la rentabilidad económica.
Generación de vectores de probabilidad y de rentabilidad.
Gasto adicional por fungicidas, herbicidas, insecticidas, etc.

    Sería muy útil saber los rangos de fechas en los que los cultivos están en condiciones adversas y su crecimiento/calidad/productividad se pudiera ver afectado.

Agropy surge del [Hackathon CoAfina 2022](https://laconga.redclara.net/hackathon/), somos un grupo motivado

![](https://laconga.redclara.net/hackathon/static/media/logo-co-afina.196c0780.png)


Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.
