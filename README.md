# Cluster-de-Comportamiento-del-COVID-19
Explorar el uso de la librería Trendy y el algoritmo Dynamic Time Warping (DTW) para analizar series temporales de casos de COVID-19. A través del clustering y la estandarización de fechas de inicio, proyectamos el comportamiento de la pandemia en diferentes países.


## Introducción

La pandemia de COVID-19 tuvo impacto global sin precedentes, afectando a países de todo el mundo de manera heterogénea. El análisis de la evolución de la enfermedad a nivel mundial es fundamental para comprender cómo se propaga y afecta a diferentes regiones. Sin embargo, la variabilidad en las fechas de inicio de contagios en cada país complica la comparación y el análisis de patrones de propagación.

En este trabajo, se utiliza el algoritmo Trendy junto con el algoritmo Dynamic Time Warping (DTW) para estandarizar y analizar la evolución de contagios por COVID-19 en diferentes países. Esta metodología permite agrupar países con patrones de propagación similares, independientemente de cuándo comenzaron a registrar casos.

# Metodología

## Paso 1: Clusterización Basada en Cantidad de Contagios Diarios

Se aplicó un algoritmo de clustering a nivel mundial utilizando la cantidad de contagios diarios de COVID-19 en diferentes países. El objetivo era agrupar países con patrones de propagación similares.

## Paso 2: Estandarización Temporal

Para comparar de manera efectiva los patrones de contagio, se realizó un procedimiento de estandarización temporal. Todos los países fueron llevados a un mismo punto de inicio, como si comenzaran al mismo tiempo. Esto es esencial para eliminar el sesgo causado por las diferencias en las fechas de inicio de contagios en cada país.

## Paso 3: Proyección del Comportamiento Futuro

Una vez que se agruparon los países con patrones de propagación similares, se proyectó su comportamiento futuro en función de la evolución de otros países dentro del mismo grupo. Por ejemplo, si un país inició sus contagios el 01-03-2020 y otro el 01-04-2020, podemos anticipar que el estado actual del primero será similar al del segundo aproximadamente un mes después.


## Resultados y Discusión

La aplicación del algoritmo Trendy y DTW ha enriquecido el análisis de COVID-19 al permitir agrupar países con patrones de contagio similares y proyectar su evolución futura con mayor precisión. Esta metodología es una herramienta valiosa para el análisis de series temporales en situaciones donde las secuencias varían en velocidad y duración. Al agrupar países en función de sus patrones de propagación, podemos anticipar cómo evolucionará la pandemia en diferentes regiones del mundo. Este algoritmo Trendy, tambien puede replicarse para conocer o saber como sera el comportamiento de nuestros productos en nuevos mercado... interesante...

## Conclusión

En resumen, este enfoque de clustering y estandarización temporal utilizando el algoritmo Trendy y DTW brinda una visión más clara de la evolución de la pandemia de COVID-19 a nivel mundial. permite proyectar cómo se comportará la enfermedad en diferentes países en función de sus patrones de propagación. Además, el uso de Trendy y DTW resalta la importancia de las herramientas de análisis de series temporales en la comprensión y gestión de crisis sanitarias como la actual pandemia

Este enfoque se ha aplicado específicamente para evaluar el impacto del COVID-19 en Perú, al igualar la fecha de inicio de todos los países.


