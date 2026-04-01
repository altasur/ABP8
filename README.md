## Clasificador de Ropa StyleNet - Deep Learning

Este proyecto implementa una **Red Neuronal Convolutiva (CNN)** en Python utilizando TensorFlow/Keras para clasificar automáticamente imágenes de prendas de vestir.

##  Características
- **Dataset:** Fashion-MNIST (70,000 imágenes).
- **Arquitectura:** CNN con capas de Dropout para evitar overfitting.
- **Precisión:** ~90% en datos de validación.

##  Resultados
El modelo logra diferenciar con éxito categorías complejas como Camisas vs. Camisetas. Se incluyen curvas de precisión y pérdida que demuestran la estabilidad del entrenamiento.

##  Tecnologías
- Python 3
- TensorFlow / Keras
- Matplotlib / Seaborn (Visualización)
- Google Colab (Entrenamiento en GPU)

## Cómo usar
1. Clonar el repo.
2. Abrir el archivo `.ipynb` en Google Colab.
3. Ejecutar todas las celdas para ver el entrenamiento y las predicciones finales.