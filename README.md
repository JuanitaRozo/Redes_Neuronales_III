# Redes Neuronales III

Repositorio con tres prácticas de redes neuronales aplicadas a la clasificación de prendas del conjunto de datos Fashion-MNIST usando Python, TensorFlow y Keras.

## Descripción

Este proyecto explora diferentes aspectos del entrenamiento y evaluación de redes neuronales artificiales para clasificación de imágenes:

- preparación y análisis del conjunto de datos
- construcción de modelos secuenciales
- comparación de optimizadores
- regularización y early stopping
- evaluación con métricas de clasificación
- visualización de resultados y matriz de confusión

## Contenido del repositorio

- `Practica1.ipynb`  
  Introducción al dataset Fashion-MNIST, carga de datos, separación de entrenamiento/validación, normalización y visualización de muestras.

- `Practica2.ipynb`  
  Construcción de una red neuronal feedforward con capas densas, comparación entre optimizadores SGD y Adam, y análisis de precisión y pérdida durante el entrenamiento.

- `Practica3.ipynb`  
  Comparación entre un modelo base y un modelo regularizado con L2 + Dropout, uso de Early Stopping, evaluación final en conjunto de prueba y análisis de métricas por clase.

## Tecnologías utilizadas

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- scikit-learn
- Jupyter Notebook

## Objetivo del proyecto

Diseñar, entrenar y comparar modelos de redes neuronales para resolver un problema de clasificación multiclase sobre imágenes de ropa, analizando cómo afectan distintos hiperparámetros y técnicas de regularización al rendimiento del modelo.

## Requisitos

Para ejecutar los notebooks localmente se recomienda:

- Python 3.9 o superior
- Jupyter Notebook o JupyterLab
- TensorFlow
- NumPy
- Matplotlib
- scikit-learn

## Instalación

```bash
python -m venv venv
source venv/bin/activate   # Linux/macOS
# o en Windows:
# venv\Scripts\activate

pip install tensorflow numpy matplotlib scikit-learn notebook
```

## Ejecución

### Opción 1: Localmente

```bash
jupyter notebook
```

Luego abre cualquiera de los archivos `.ipynb` del repositorio.

### Opción 2: Google Colab

Puedes abrir cada notebook directamente desde GitHub en Colab usando el enlace que aparece en la parte superior de cada archivo.

## Resultados destacados

En las prácticas se evaluó el rendimiento de los modelos sobre Fashion-MNIST, obteniendo resultados competitivos con una arquitectura de red neuronal densa. El modelo final de la práctica 3 reportó métricas cercanas a:

- Accuracy: 0.87
- Precision: 0.88
- Recall: 0.87
- F1-score: 0.87

## Estructura general del flujo de trabajo

1. Carga del dataset Fashion-MNIST
2. División de datos en entrenamiento, validación y prueba
3. Normalización de imágenes
4. Construcción de arquitecturas de redes neuronales
5. Entrenamiento y comparación de optimizadores/modelos
6. Evaluación con métricas y visualización de resultados

## Autor

Proyecto desarrollado por Juanita Rozo.

## Licencia

Este repositorio se comparte con fines académicos y de aprendizaje. Si deseas reutilizar el contenido, puedes citarlo y mencionarlo como referencia.
