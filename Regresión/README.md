# Predicción de Muertes por Cáncer de Pulmón en México

Este proyecto forma parte del programa **Samsung Innovation Campus 2024** y tiene como objetivo principal predecir el número de muertes por cáncer de pulmón en México utilizando modelos de aprendizaje automático y profundo. Se comparan dos enfoques: un modelo de Regresión Lineal y una Red Neuronal Recurrente (LSTM).

## Objetivo del Proyecto

Analizar la evolución histórica de las muertes por cáncer de pulmón en México desde 1990 hasta 2016, y predecir el número de muertes hasta el año 2040 mediante modelos supervisados. Se pretende generar un modelo confiable que pueda ser útil para instituciones de salud en la planificación de recursos y estrategias de prevención.

## Modelos Implementados

### 1. Regresión Lineal

- Basado en la relación lineal entre el año y el número de muertes.
- Se ajusta una recta a los datos históricos.
- Métricas utilizadas:
  - Error cuadrático medio (MSE)
  - Coeficiente de determinación \( R^2 \)
- **Predicción para el año 2040**: `10,461` muertes.

### 2. Red Neuronal Recurrente (LSTM)

- Modelo de Deep Learning que permite capturar relaciones temporales complejas.
- Arquitectura:
  - 1 capa LSTM
  - 1 capa densa
- Datos normalizados antes del entrenamiento.
- Métricas de evaluación: MSE y comparación visual.
- **Predicción para el año 2040**: `7,815` muertes.

## 📈 Visualizaciones
La notebook incluye múltiples visualizaciones para interpretar los resultados:

Gráfico de dispersión de datos históricos.

Predicción lineal con proyección al 2040.

Gráficos de pérdida de entrenamiento y predicción LSTM.

Comparación visual entre ambos modelos.

## Conclusiones
El modelo de Regresión Lineal proyecta un crecimiento constante en la mortalidad, con una predicción más alta que el modelo LSTM.

El modelo LSTM captura dinámicas más complejas y sugiere una tendencia ligeramente más baja.

Ambos modelos ofrecen resultados plausibles y cercanos a cifras reales reportadas, lo que valida la calidad del análisis.

## 🛠️ Tecnologías y Librerías

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras

## Autor
Emilio Zdenko Abarca Cruz – UAEMex

## Instalación

Clona este repositorio y ejecuta los notebooks en un entorno con las dependencias correctas:

```bash
git clone https://github.com/tu-usuario/Prediction_Lung_Cancer.git
cd Prediction_Lung_Cancer
pip install -r requirements.txt
