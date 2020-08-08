# Analisis por Clasificacion Binaria Covid-19

## Estructura del Repositorio:

En la carpeta Analisis_Covid19

- Graficas: Salida del Dataset preprocesado y la del cluster.
- AnalisisClasificacionBinariaRFC: Archivo formato .ipynb, "Cuaderno de Jupyter" donde podrá evidenciar todo el método programado y experimentar según su conveniencia.
-AnalisisClasificacionBinariaRFC: .Archivo formato .html "Cuaderno de Jupyter en formato HTML"
- DataSets.rar: Aqui se encuentran las csv del dataset procesado, y del cluster


Se implementó un modelo Random Forest con la finalidad de predecir el resultado de los pacientes con Covid-19 positivo, nos hemos basado en 47 variables, además de esto se hizo clustering para obtener grupos con características similares, posteriormente se decidió trabajar un grupo específico en donde se contienen la mayor parte de pacientes con covid-19 positivo. 

El conjunto de datos original se tomó de: https://www.covid19survivalcalculator.com/download

- DataSetConEtiquetas_Grupo7.csv -> conjunto de datos del cluster
- master_dataset_limpienzaDatos.csv -> Dataset que se obtuvo realizando clustering en el dataset original

## Pasos para reproducir resultados:

1. Primero se debería de revisar la información que se encuentra en el cuaderno de Jupyter Covid19_BarreraJ_BarreraK _ProyectoFinal.ipynb en este cuaderno se encuentra:  

- Categorización de Variables 
- Limpieza de ruido 
- Transformación de variables (normalización)
- Reducción de dimensionalidad de todo el conjunto para obtener variables relacionadas 
- Realizar clustering para categorizar a las personas de nuestro dataset
- Elección de un nuevo dataset en donde se encuentran la mayor cantidad de personas con covid-19 positivo 

2. Segundo se debería de revisar la información que se encuentra en el cuaderno de Jupyter Covid19TrabajandoConSubDataSet.ipynb en este cuaderno se encuentra: 

- Medidas descriptivas del Dataset(media, desviación estándar, varianza y correlaciones de cada variable) 
- Método de Aprendizaje Random Forest para predecir si una persona posee covid-19
- Clustering
- Medidas de calidad: accurancy, f1, recall y precisión. 
- Importancia de variables antes y después de aplicar pca con 39 componentes principales. 
- Correlación de personas que fueron confirmadas con covid-19

## Requirements
- Python 3.7.6
## Dependencies
- pandas 
- matplotlib 
- numpy 
- sklearn, etc
