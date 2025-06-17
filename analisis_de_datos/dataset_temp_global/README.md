# Dataset Temperatura Global de la Tierra (Global Land Temperature, GLT)
El conjunto de datos de Temperatura Global de la Tierra (Global Land Temperature,
GLT) es una gran colección de mediciones mantenidas activamente
por Berkeley Earth (https://berkeleyearth.org/data/). Contiene los datos
fuente en bruto medidos con estaciones alrededor del mundo, además de un
formato intermedio y varios archivos de salida formateados. Los datos abarcan
desde aproximadamente 1750 hasta días recientes con disponibilidad mensual
y diaria. Las mediciones se proporcionan por hemisferios, estados, países, ciudades
y más.

En el código se trabaja con una versión modificada, más pequeña pero más difícil, del conjunto
de datos original de GLT, para destacar la importancia de la preprocesamiento
de datos. Más específicamente, esta versión didáctica contiene los
archivos de salida formateados de las principales ciudades del mundo con granularidad
mensual. Por simplicidad, el análisis abarcará casi dos siglos (es decir,
entre los años 1817 y 2012).

El conjunto de datos está compuesto por aproximadamente 200,000 filas correspondientes
a las mediciones tomadas el primer día del mes en una ciudad dada.
Cada medición se describe con 7 valores:

- Fecha, cuando se tomó la medición
- Temperatura Media (AverageTemperature)
- Incertidumbre de la Temperatura Media (AverageTemperatureUncertainty)
- Ciudad, desde donde se tomó la medición
- País
- Latitud
- Longitud

El conjunto de datos está disponible en formato CSV con el nombre

GLT_filtrado.csv

Este archivo tiene errores puestos deliberadamente con el objetivo de dar estrategias para llenar muchos datos faltantes de forma lógica con el problema y también buscar errores o datos que no tengan sentido para el contenido del dataset y así poder corregirlos.
