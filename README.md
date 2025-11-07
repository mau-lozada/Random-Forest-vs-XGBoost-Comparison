# 🌲 Random Forest vs XGBoost – Modelos de Regresión

Comparativa práctica entre **Random Forest Regressor** y **XGBoost Regressor**, aplicados al dataset de viviendas de California.  
El objetivo fue analizar la precisión, velocidad de entrenamiento y predicción de ambos modelos.

---

## 🧠 Objetivo del proyecto  

Predecir el **precio medio de viviendas** en diferentes zonas de California, utilizando variables como:  
- Ingresos medios  
- Edad media de las casas  
- Habitaciones y dormitorios promedio  
- Población y ocupación  
- Latitud y longitud  

---

## ⚙️ Tecnologías utilizadas  

- Python 🐍  
- Scikit-learn  
- XGBoost  
- NumPy  
- Matplotlib  

---

## 📈 Entrenamiento y evaluación  

Ambos modelos fueron entrenados con **100 árboles (`n_estimators=100`)** y los mismos datos de entrenamiento/test.  
Se evaluaron los modelos usando las métricas **MSE** y **R²**:

| Modelo | MSE | R² | Tiempo de predicción |
|:-------|:----:|:--:|:--------------------:|
| Random Forest | 0.2554 | 0.8051 | 0.1664 s |
| XGBoost | **0.2226** | **0.8301** | **0.0090 s** |

---

## 🧠 Conclusión  

**XGBoost** mostró un rendimiento superior en precisión y velocidad,  
gracias a su enfoque de *boosting secuencial* que reduce el sesgo y mejora la generalización.  
Ideal para tareas de regresión complejas con datos de alta dimensionalidad.

---

## ☁️ Abrir en Google Colab  

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mau-lozada/Random-Forest-vs-XGBoost-Comparison/blob/main/RandomForest_XGBoost.ipynb)

---
✍️ *Autor: Mauricio Lozada*  
📌 *Repositorio en desarrollo para portafolio de Machine Learning.*
