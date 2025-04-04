# Proyecto Final – Samsung Innovation Campus 2024  
## **"Detección de cáncer de pulmón con un enfoque basado en aprendizaje automático y profundo"**

Repositorio del proyecto final desarrollado por el **Equipo 2, Grupo 3** como parte del programa **Samsung Innovation Campus 2024**. Este proyecto aplica técnicas de *Machine Learning* y *Deep Learning* para detectar, predecir y analizar datos sobre el cáncer de pulmón.

## Autores 
Equipo 2, Grupo 3:
- Emilio Zdenko Abarca Cruz
  
Licenciatura en Ingeniería en Computación, Universidad Autónoma del Estado de México
- Francisco Javier Aburto López
  
Matemáticas Aplicadas y Computación, Facultad de Estudios Superiores Acatlán
- Carlos Fuentes Herrera
  
Ingeniería en Mecatrónica, Unidad Profesional Interdisciplinaria en Ingeniería y Tecnologías Avanzadas (UPIITA-IPN)
- Enrique Ramírez Rodríguez
  
Matemáticas Aplicadas y Computación, Facultad de Estudios Superiores Acatlán

---

## Descripción del Proyecto

Se desarrollaron modelos para:

- Clasificación de pacientes con alto riesgo.
- Predicción del número de muertes hacia el año **2040**.
- Agrupamiento de la población con base en características clave.

Se utilizaron algoritmos como:

- *Random Forest*  
- *Regresión Lineal*  
- *Red Neuronal Recurrente (LSTM)*  
- *K-Means*

---

## Tecnologías y Herramientas

- Python 3  
- Scikit-learn  
- TensorFlow / Keras  
- Pandas, NumPy, Matplotlib, Seaborn  
- Jupyter Notebook  
- Git & GitHub  

---

## Modelos Implementados

### Clasificación

- **Algoritmos utilizados:** Árbol de Decisión, Random Forest, SVM  
- **Mejor desempeño:** Random Forest con **89%** de precisión  
- **Métricas evaluadas:** Precision, Recall, F1-score

---

### Predicción

- **Modelos usados:** Regresión Lineal y Red Neuronal LSTM  
- **Año objetivo:** `2040`  
- **Resultados:**
  - Regresión Lineal → `10,461` muertes estimadas  
  - LSTM → `7,815` muertes estimadas  
- **Métrica de comparación:** `MSE (Mean Squared Error)`  
- **Conclusión:** El modelo de Regresión Lineal obtuvo menor MSE, lo que indica mayor precisión para este caso.

---

### Agrupamiento

- **Algoritmo:** K-Means  
- **Segmentación:** 3 grupos definidos por edad, comorbilidades y ubicación geográfica  
- **Visualización:** Se utilizaron mapas de calor y gráficos de dispersión para representar los grupos generados.

