# CAMI CAmpesinos y Mediciones ambientales

### Más allá de un desafío: nuestra motivación

El equipo Agropy del Hackathon CoAfina 2022 asume reto de MakeSens para dar respuesta inmediata a los campesinos de Latinoamérica de los cultivos más viables de acuerdo a datos medioambientales actualizados. De esta manera, desarrollamos CAMI (CAmpesinos y Mediciones ambIentales), un algoritmo diseñado para calcular los porcentajes de éxito de siembra de diferentes cultivos de acuerdo a parámetros como temperatura, humedad y precipitación.

Pero, somos más que líneas de código, queremos aportar nuestras semillas de conocimiento y tecnología para la agricultura sustentable ¡Crecemos juntos!

### Germinamos con datos

En Agropy creemos en las soluciones innovadoras, pero sabemos que tecnificar el sector agrario es un reto en sí mismo. Escoger los cultivos a sembrar en determinadas épocas del año lleva a un estudio de factores climáticos, el cual es complejo y multivariable. Esto lleva a la creación de CAMI, un algoritmo que aprovecha el vasto mundo de bases de datos de mediciones ambientales para su análisis e interpretación.

---

### El cógido [CAMI](https://github.com/ramosmaria/Reto-2-Agropy/blob/main/CAMI-Agropy_codigo.ipynb):

#### Entradas:
Usuario: Fecha inicial y final.
Empresa: Código de la estación climatológica (de acuerdo al lugar de interés), Token, parámetros a tomar y pesos de los parámetros (Temperatura, Humedad y precipitación), Datasets Cultivos.
#### Fases:

##### Fase de comparación:
- Se contrastan las condiciones ambientales registradas por la estación EVA con la base de datos de los parámetros óptimos para el éxito de cada cultivo.
##### Fase de puntuación:
- De acuerdo a la cercanía de las condiciones de la estación con la base de datos o parámetros óptimos de los cultivos le asigna un puntaje a cada una de las dimensiones (parámetros considerados)
- El puntaje total es la suma ponderada de los puntajes de cada dimensión. Es decir, se le asigna un peso a cada parámetro a cada dimensión.
##### Fase de recomendación:
- Se ofrece un listado que muestra los cultivos, ordenados de acuerdo al puntaje obtenido. Aquellos mejor clasificados son opciones que requieren menos cuidados para que su cosecha sea exitosa.
-Se presenta este listado de recomendación para diversos periodos
-Se presenta un listado de recomendación por mes dentro del periodo de tiempo requerido por el usuario.

##### Salidas:
Orden de los cultivos por probabilidad de éxito de acuerdo a condiciones climáticas por meses.

##### Otras propuestas:
Considerar el parámetro de humedad como un factor de proliferación de hongos y hiervas, que afectan al desarrollo de los cultivos y, por tanto, en su rentabilidad económica.

##### Recomendaciones:
Generar una nueva manera de hacer la penalización en la comparación del filtrado de los parámetros.
Nueva manera de andar por los rangos de fechas.


---

### [Reporte estadítico](https://github.com/ramosmaria/Reto-2-Agropy/blob/main/Reporte_tecnico_ambiente.html). ¡Descarga y correlo en el navegador!
