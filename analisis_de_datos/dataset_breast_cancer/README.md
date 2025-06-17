# Dataset Wisconsin Diagnostic Breast Cancer (WDBC)
Se trabaja con el conjunto de datos Wisconsin Diagnostic Breast
Cancer (WDBC) usando pandas y con la correlación lineal de Pearson.

El conjunto de datos de cáncer de mama, accesible desde https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic es
utilizado para predecir si un tumor es maligno o benigno basándose en 30 características numéricas obtenidas de imágenes digitalizadas de células. 
Estas características describen propiedades físicas como el radio, la textura, el perímetro,
el área, y la suavidad de los núcleos celulares.

El conjunto de datos incluye un total de 569 muestras y est´a clasificado en dos
clases:
- Maligno: Tumor canceroso (clase 0).
- Benigno: Tumor no canceroso (clase 1).

El conjunto incluye 30 características calculadas para cada imagen de una masa
mamaria, derivadas de imágenes digitalizadas de aspiraciones con aguja fina
del tejido mamario. Estas características describen propiedades de los núcleos
celulares en la imagen.

- Características medias (3-12): Representan el valor promedio de cada
característica para todos los núcleos celulares en la imagen.
- Error estándar (13-22): Representa el error estándar de la característica medida, proporcionando una estimación de la variación.
- Peores características (23-32): Se calculan como la media de los tres valores más grandes de cada característica en una imagen.

Entre las principales características numéricas presentes en el conjunto de datos
se encuentran:
- radio medio: Distancia media desde el centro hasta los puntos del perímetro.
- textura media: Desviación estándar de los valores de escala de gris.
- perímetro medio: Medida promedio del perímetro de las células.
- área media: Área promedio de las células.
- suavidad media: Variación local en la longitud de los radios.

Vamos a estudiarlo el conjunto usando pandas.
