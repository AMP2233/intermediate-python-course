
---

# Proyecto de Clasificación de Imágenes con Python y TensorFlow

Este proyecto se enfoca en desarrollar un clasificador de imágenes utilizando TensorFlow, específicamente una Red Neuronal Convolucional (CNN). El objetivo es trabajar con el conjunto de datos MNIST, compuesto por imágenes de números manuscritos.

## Contenido

1. **Descripción y Muestras del Set de Datos**
    - Descarga del Set de Datos
    - Contenido del Dataset
    - Preprocesamiento de Imágenes
    - Visualización de Imágenes del Set de Datos
    
2. **Creación del Modelo**
    - Estructura del Modelo
    - Compilación del Modelo
    - Entrenamiento del Modelo
    - Visualización de Pérdida y Precisión
    
3. **Arquitectura de la Red Neuronal**
    - Diagrama de Bloques de la CNN
    
4. **Análisis y Evaluación del Modelo**
    - Curvas de Precisión y Pérdida
    - Curva de Tasa de Aprendizaje vs. Pérdida
    - Matriz de Confusión
    
## Detalles del Proyecto

Este proyecto utiliza TensorFlow y TensorFlow Datasets para trabajar con el conjunto de datos MNIST. Se lleva a cabo un proceso de preprocesamiento de imágenes, normalizando los valores de píxeles para mejorar el rendimiento del modelo. Se desarrolla una CNN con capas convolucionales, de agrupación y completamente conectadas para clasificar las imágenes.

El modelo se compila utilizando la función de pérdida de entropía cruzada categórica dispersa y el optimizador Adam. Posteriormente, se procede con el entrenamiento del modelo durante varias épocas, observando la evolución de la pérdida y la precisión.

Se visualiza la arquitectura de la red neuronal utilizada, se analiza la tasa de aprendizaje y la pérdida, y se evalúa el rendimiento del modelo mediante una matriz de confusión.

El proyecto proporciona una comprensión detallada del proceso de clasificación de imágenes utilizando TensorFlow y CNNs, mostrando visualizaciones y evaluaciones del modelo para comprender su comportamiento y precisión.

---
