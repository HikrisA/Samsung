# Documentación del apartado clasificación del proyecto para el Samsung Innovation Campus 2024

Este apartado del proyecto contiene varios modelos para la clasificación de cáncer de pulmón utilizando técnicas de **Machine Learning** y **Deep Learning**. Hay que considerar que para la creación de los conjuntos de datos, se deben tener las imágenes descargadas y en 3 carpetas separadas, siendo estas 3 carpetas cada clase. A continuación, se describen los archivos que conforman el apartado de clasificación.

## Notebooks

### Notebook_support_vector_classifier.jpynb
Este notebook contiene el modelo de SVC, la creación de conjuntos de entrenamiento y validación, su entrenamiento y evaluación.

#### Descripción:
- **Algoritmo**: *Support Vector Classifier*.
- **Entrada**: Imágenes histopatológicas de tumores de cáncer de pulmón.
- **Salida**: Clasificación del tipo de cáncer de pulmón.

#### Instrucciones:
1. Reemplazar en la segunda celda de código la dirección donde se localizan las 3 carpetas con imágenes.
2. Entrenar el modelo y posteriormente si es necesario cambiar parámetros del mejor modelo.
3. Evaluar el modelo.

### Notebook_RL_XGBClassifier.jpynb
Este notebook contiene los modelos de regresión logística y *XGBClassifier*, la creación de conjuntos de entrenamiento y validación, su entrenamiento y evaluación.

#### Descripción:
- **Algoritmos**: Regresión Logística y *XGBClassifier*.
- **Entrada**: Imágenes histopatológicas de tumores de cáncer de pulmón.
- **Salida**: Clasificación del tipo de cáncer de pulmón.

#### Instrucciones:
1. Reemplazar en la segunda celda de código la dirección donde se localizan las 3 carpetas con imágenes.
2. Entrenar los modelos y posteriormente si es necesario cambiar parámetros del mejor modelo.
3. Evaluar los modelos.

### Notebook_redes_neuronales_clasificación.jpynb
Este notebook contiene diferentes modelos de CNN's, la creación de conjuntos de entrenamiento y validación, su entrenamiento y evaluación.

#### Descripción:
- **Algoritmos**: Modelos de CNN's con ténicas de *Transfer Learning*, *Fine Tuning* y un modelo propuesto.
- **Entrada**: Imágenes histopatológicas de tumores de cáncer de pulmón.
- **Salida**: Clasificación del tipo de cáncer de pulmón.

#### Instrucciones:
1. Reemplazar en la segunda celda de código la dirección donde se localizan las 3 carpetas con imágenes.
2. Entrenar los modelos, se debe considerar que existe una variable única *modelo* para evitar saturar la memoria, es decir, solo se puede tener un modelo en memoria.
3. Evaluar los modelos.

## Requisitos del Proyecto

### Versión de Python
Este proyecto ha sido probado con **Python 3.8.0**. Se recomienda usar esta versión para evitar posibles problemas de compatibilidad con las librerías.
Este proyecto realizó el entrenamiento con GPU para los modelos que lo permitían y utilizó las siguientes versiones de CUDA y cuDNN:
- **CUDA**: 11.8
- **cuDNN**: 8.6.0 (compatible con CUDA 11.8)

### Dependencias
Para instalar las dependencias necesarias, puedes usar el archivo `requirements.txt` con el siguiente comando:

```bash
pip install -r requirements.txt