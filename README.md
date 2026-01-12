Proyecto 2 Visualizacion de datos Jerley Andres Mejia

Este repositorio contiene el código y los datos utilizados para la creación, limpieza y preparación del conjunto de datos empleado en la práctica de Visualización de Datos.

El procesamiento de los datos se ha realizado en Python y los archivos resultantes se utilizan posteriormente para la construcción de visualizaciones interactivas en Flourish.

CONTENIDO DEL REPOSITORIO

ProVisualizacionJerleyAndresMejia.ipynb
Notebook en Python donde se realiza la carga, limpieza y transformación del dataset original. En este archivo se generan los CSV finales utilizados en las visualizaciones.

capacity.csv
Archivo con información relacionada con la capacidad productiva de las minas (value tonnes), empleado para analizar la relación entre localización y capacidad productiva.

minerals.csv
Dataset con información sobre los tipos de minerales (primary commodity / material) asociados a las instalaciones mineras.

reserves.csv
Archivo con datos de reservas minerales agregadas por país y tipo de mineral, utilizado para comparar volúmenes totales de producción en la Unión Europea.

facilities.gpkg
Archivo geoespacial que contiene información de las instalaciones mineras y de procesamiento, incluyendo localización (cuando está disponible), tipo de instalación (facility type) y país.

OBJETIVO DEL PROYECTO

El objetivo del proyecto es explorar y analizar la actividad minera en la Unión Europea mediante visualizaciones interactivas, respondiendo preguntas relacionadas con:

La concentración geográfica de las instalaciones mineras.

Los minerales predominantes en cada país.

La relación entre localización y capacidad productiva.

La distribución de la producción total por tipo de mineral y país.

Este repositorio se centra exclusivamente en la fase de preparación y tratamiento de los datos.

TECNOLOGÍAS UTILIZADAS

Python

Pandas

GeoPandas

Jupyter Notebook

FUENTE DE LOS DATOS

Los datos utilizados proceden de fuentes públicas:

Zenodo: https://zenodo.org/records/6325109

Global Energy Monitor – Global Coal Mine Tracker

FINEPRINT Geovisualisations: https://www.fineprint.global/visualisations/viewer/

AUTOR

Jerley Andrés Mejía Gallo
Máster en Ciencia de Datos
Universitat Oberta de Catalunya (UOC)
