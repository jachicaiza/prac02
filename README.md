# prac02
Práctica 02 - Tipología de datos

Integrantes:
* Janneth Chicaiza
* Jaime Velandia

En este sitio se encuentra la documentación y los datos relacionados a la Práctica 2 de Tipología de Datos.

## Origen y estructura de datasets

Se elegió el dataset [Heart Disease](https://archive.ics.uci.edu/ml/datasets/heart+Disease) el cual comprende varios archivos de datos proporcionados por diferentes instituciones de salud. La base de datos contiene 14 atributos y corresponde a información de pacientes recolectada por instituciones como: Cleveland Clinic Foundation, Hungarian Institute of Cardiology, University Hospital of Zurich, y University Hospital de Basel. Para la presente práctica, se han tomando como base los datos de las dos primeras instituciones. El dataset contiene una serie de observaciones de pacientes clasificados de acuerdo a si tienen alguna enfermedad cardíaca o no. Los datos puede ser descargados desde [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/)


## Resultados

A partir de las tres preguntas planteadas, se puede concluir que:

1. ¿Cuáles son las variables que más influyen en una enfermedad relacionada al corazón?. A partir del análisis de correlación y correspondencia se puede establecer que cada uno de los 10 atributos explican en cierta proporción la variabilidad de la clase. El único atributo menos influyente sería el colesterol.
2. ¿El tipo de dolor torácico del paciente (cp) es un indicativo de posible problema del corazón?. A través del análisis de cada tipo de dolor (cp) que adolece el paciente, se comprobó que si el paciente no presenta dolor (asintomático) existen menos probabilidades de que esté padeciendo de un problema del corazón.
3. ¿Qué tan efectivo es un modelo de regresión logística para predecir el padecimiento del corazón en el caso de hombres y de mujeres? A través de un modelo de regresión se pudo probar la efectividad del modelo para predecir la clase por sexo. En el caso de las mujeres, el modelo alcanza el 100% de precisión, mientras que en el caso de hombres llega a un poco más del 80%, es decir, en el caso de los hombres pueden existir otras variables que no se tomaron en cuenta en el análisis y que inciden en el estado de su salud cardiaca.

## Licencia

El contenido de este proyecto está licenciado bajo Apache License. Apache License es un tipo de licencia copyleft, ya que no requiere la redistribución del código fuente cuando se distribuyen versiones modificadas. Al elegir este tipo de licencia se espera contribuir a la mejora de los datos y modelos creados en esta práctica.
