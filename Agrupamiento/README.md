# Documentación del apartado del agrupamiento del proyecto para el Samsung Innovation Campus 2024

En este apartado se encuentran los modelos de agrupamiento que se utilizaron para trabajar con el dataset 

## Objetivo

Agrupar a los pacientes en 3 clústeres para poder identificar de manera precisa si un paicente tiene un nivel de cáncer bajo, medio o alto.

## Dataset utilizado 

[Lung Cancer Prediction](https://www.kaggle.com/datasets/thedevastator/cancer-patients-and-air-pollution-a-new-link/data)

## Contenido del notebook

En el notebook se encuentran

- Agrupamiento de datos con k-means
  
- Reducción de dimensionalidad con PCA

- Agrupamiento de datos con DBSCAN

-  Evaluación de ambos modelos de agrupamiento

### Parámetros modificables 

Como se menciona en el objetivo, la intención de tener 3 clústeres es agrupar a los pacientes por el nivel de enfermedad que tengan, debido a esto, se buscaron los parámetros que nos permitieran agrupar los datos en 3 Clústeres para el método de DBSCAN. Por  esta razón, utilizar un número distinto para cualquiera de los modelos ocasionaría que la interpretación fuera compleja o que no tenga sentido. 

## Versión de las librerías utilizadas

- Pandas versión: 2.2.2
	
- NumPy versión: 2.0.2
	
- Seaborn versión: 0.13.2
	
- Matplotlib versión: 3.10.0
	
- Sklearn versión: 1.6.1
	
- SciPy versión: 1.14.1
