# Random-Forest-vs-XGBoost-Comparison
🌲 Random Forest vs XGBoost – Modelos de Regresión en Machine Learning  Comparativa práctica entre Random Forest Regressor y XGBoost Regressor, aplicados al dataset de viviendas de California. El objetivo fue analizar la precisión, velocidad de entrenamiento y predicción de ambos modelos.

Objetivo del proyecto

Predecir el precio medio de viviendas en diferentes zonas de California, utilizando variables como:

Ingresos medios

Edad media de las casas

Habitaciones y dormitorios promedio

Población y ocupación

Latitud y longitud

Se busca comparar el desempeño entre Random Forest y XGBoost, dos algoritmos de ensamble ampliamente utilizados en Machine Learning.

⚙️ Tecnologías utilizadas

Python 🐍

Scikit-learn

XGBoost

NumPy

Matplotlib

🚀 Entrenamiento y evaluación

Ambos modelos fueron entrenados con 100 árboles (n_estimators=100) y los mismos datos de entrenamiento/test.
Se evaluaron los modelos usando las métricas:

MSE (Mean Squared Error)

R² (Coeficiente de determinación)

Tiempos de entrenamiento y predicción

📊 Resultados obtenidos:

Modelo	MSE	R²	Tiempo de predicción
Random Forest	0.2554	0.8051	0.1664 s
XGBoost	0.2226	0.8301	0.0090 s
📈 Visualización

La siguiente gráfica compara los valores reales frente a los predichos para ambos modelos.
La línea negra representa el modelo perfecto, y las rojas indican ±1 desviación estándar.

🔹 Interpretación:

XGBoost presenta puntos más cercanos a la línea ideal → mejor precisión.

Random Forest muestra mayor dispersión → más error residual.

🧠 Conclusiones

Random Forest reduce la varianza y evita sobreajuste, pero puede quedarse corto en precisión.

XGBoost, gracias a su enfoque secuencial (boosting), reduce el sesgo y mejora la generalización.

En este caso, XGBoost fue más preciso y rápido, por lo que resulta más adecuado para tareas de regresión con alta dimensionalidad o necesidad de optimización fina.

☁️ Abrir en Google Colab

🔹 Notebook completo:


✍️ Autor: Mauricio Lozada
📌 Repositorio en desarrollo para portafolio de Machine Learning.
