[LauraBastidas, predicción Churn.ipynb](https://github.com/user-attachments/files/29401145/LauraBastidas.prediccion.Churn.ipynb)
# prediccion-churn-red-neuronal
Modelo de clasificación binaria (Keras/TensorFlow) para predecir la probabilidad de abandono de clientes, sobre una base de 10,000 registros
# Predicción de Churn con Redes Neuronales

Modelo de clasificación binaria (Keras/TensorFlow) para predecir la probabilidad
de abandono de clientes, sobre una base de 10,000 registros.

## Proceso
- Preprocesamiento: codificación de variables categóricas y escalado (StandardScaler)
- Arquitectura: red neuronal Sequential, 2 capas ocultas
- Evaluación: matriz de confusión, accuracy

## Resultado
86.85% de accuracy en el set de prueba. El análisis de la matriz de confusión
identificó que el principal reto del modelo está en los falsos negativos,
un problema crítico en cualquier estrategia real de retención de clientes.
