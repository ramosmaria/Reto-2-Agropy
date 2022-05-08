---
title: El Código
layout: template
filename: cami-codigo
---


# ¡Explora nuestro código!

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ramosmaria/Reto-2-Agropy/HEAD)

## Hablemos de código

### Entradas

**Usuario:** Fecha inicial y final.  
**Empresa:** Código de la estación climatológica (de acuerdo al lugar de interés), Token, parámetros a tomar y pesos de los parámetros (Temperatura, Humedad y precipitación), Datasets Cultivos.


### Fases

**Fase de comparación**
* Se contrastan las condiciones ambientales registradas por la estación EVA con la base de datos de los parámetros óptimos para el éxito de cada cultivo.

**Fase de puntuación**
* De acuerdo a la cercanía de las condiciones de la estación con la base de datos o parámetros óptimos de los cultivos le asigna un puntaje a cada una de * las dimensiones (parámetros considerados)
    El puntaje total es la suma ponderada de los puntajes de cada dimensión. Es decir, se le asigna un peso a cada parámetro a cada dimensión.

**Fase de recomendación**
* Se ofrece un listado que muestra los cultivos, ordenados de acuerdo al puntaje obtenido. Aquellos mejor clasificados son opciones que requieren menos cuidados para que su cosecha sea exitosa. -Se presenta este listado de recomendación para diversos periodos -Se presenta un listado de recomendación por mes dentro del periodo de tiempo requerido por el usuario.

### Salidas:

* Orden de los cultivos por probabilidad de éxito de acuerdo a condiciones climáticas por meses.


### Hacia dónde vamos

* Considerar el parámetro de humedad como un factor de proliferación de hongos y hierbas, que afectan al desarrollo de los cultivos y, por tanto, en su rentabilidad económica.
* Generar una nueva manera de hacer la penalización en la comparación del filtrado de los parámetros. Nueva manera de andar por los rangos de fechas.
