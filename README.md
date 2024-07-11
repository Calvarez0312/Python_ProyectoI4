# Biogenesys
## Descripcion del proyecto
La empresa farmacéutica BIOGENESYS busca identificar las ubicaciones óptimas para la expansión de laboratorios farmacéuticos, basándose en el análisis de datos de incidencia de COVID-19, tasas de vacunación, 
y la disponibilidad de infraestructuras sanitarias. La meta es optimizar la respuesta a los efectos de la pandemia y postpandemia con el fin de mejorar el acceso a las vacunas.

![logo empresa](https://github.com/Calvarez0312/Python_ProyectoI4/blob/main/Imagenes%20Biogenesys/Imagen%20de%20WhatsApp%202024-07-11%20a%20las%2014.37.59_25fb2a34.jpg)

## Desafio
BIOGENESYS me contratado como Data Analyst para que realice un estudio que ayudará en su estrategia de expansión en Latinoamérica específicamente en Colombia, Argentina, Chile, México, Perú y Brasil. 
Este proyecto es vital para que estén preparados y puedan tener una respuesta rápida ante cualquier situación futura que pueda surgir, la directiva ha propuesto que para poder hacer esta inversión necesitan ubicar 
regiones y recolectar datos que sean de importancia y que les ayuden a tomar decisiones. Por lo tanto, tú deberás utilizar distintas herramientas vistas en la carrera para poder ayudar a los directivos a tomar decisiones en este proceso.

## Objetivos
  • Realizar un análisis exploratorio de datos sobre la incidencia de COVID-19 y otros factores relevantes, identificando tendencias y oportunidades mediante estadísticas, mediciones y visualizaciones.
  • Aplicar técnicas de limpieza de datos para asegurar la calidad de los datos, facilitando análisis y decisiones estratégicas confiables.
  • Mejorar el acceso a los datos mediante operaciones eficientes de extracción, transformación y carga (ETL), aumentando la eficacia del análisis y la toma de decisiones.
  • Desarrollar dashboards interactivos con visualizaciones eficientes, permitiendo explorar datos desde múltiples perspectivas para una toma de decisiones informada y estratégica.

## Carga y transformacion de los datos
En este primer avance trabaje con el dataset.csv sinterizado que posee 12.216.057 filas y 50 columnas y un archivo readme que contiene el diccionario de datos, para comprender las columnas y datos relevantes.
Posteriormente filtre los datos por los paises sobre los que vamos arealizar el estudio y fechas posteriores a enero del 2021. Realice una limpieza preliminar de registros nulos y ajuste los tipos de datos segun sea necesario.
Identifique las variables claves, guarde los datos filtrados y calcule estadisticas descriptivas como la mediana, varianza y rango.

## Analisis exploratorio-Visualizacion 
En este segundo avance, calcule medidas estadisticas con Pandas y Numpy, como tendencia central, dispersion y correlaciones entre variables asi como tambien crear visualizaciones con Matplotlib y seaborn. Genere graficos como histogramas 
graficos de barra, mapas de calor y diagramas de dispersion para comprender la distribucion de la incidencia de COVID-19, las tasas de vacunacion y explorar posibles relaciones entre variables.
Identifique tendencias y patrones a largo plazo, considerando factores como la temperatura y las variaciones geograficas en la propagacion de la enfermedad. Este analisis detallado permitira identificar areas prioritarias para asiganar recuersos e implementar medidas preventivas y de control.
A continuacion algunas de las visualizaciones realizadas en el notbook.

![Varianza, mediana](https://github.com/Calvarez0312/Python_ProyectoI4/blob/main/Imagenes%20Biogenesys/Moda%2C%20varianza%2C%20etc.jpg )
![Matriz de correlacion](https://github.com/Calvarez0312/Python_ProyectoI4/blob/main/Imagenes%20Biogenesys/Matriz%20de%20correlacion.jpg)
![Histograma temperatura maxima](https://github.com/Calvarez0312/Python_ProyectoI4/blob/main/Imagenes%20Biogenesys/Histograma%20temperatura%20maxima.jpg)
![Histograma promedio Temperatura](https://github.com/Calvarez0312/Python_ProyectoI4/blob/main/Imagenes%20Biogenesys/Histograma%20promedio%20temperatura.jpg)

## EDA con Numpy y Pandas
Realice un analisis exploratorio de datos mas profundo utilizando tecnicas avanzadas de pandas y numpy. Esto implica explorar series temporales para comprender la evolucion de elementos claves del dataset, como la relacion
entre casos activos y recuperados la cobertura de vacunacion y la reduccion de casos entre otros. Este analisis detallado permite identificar patrones y tendencias adicionales, asi como tambien evaluar la efectividad de diferentes
estrategias de vacunacion y el impacto de factores como la urbanizacion y las condiciones preexistentes en la propagacion del   COVID-19.
Algunas de las visualizaciones realizadas en este avance.








