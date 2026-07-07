# Módulo 3, Unidad 2: Redes de neuronas residuales (Residual networks)

**Introducción al Deep Learning** · Duración aproximada: 75 minutos

## Contenido de esta clase

- **2.1** Redes de neuronas residuales (ResNet):
  - El problema del desvanecimiento del gradiente en redes profundas
  - Conexiones de salto (skip connections) y el bloque residual
  - Construcción con la API funcional de Keras; versiones v1 y v2
- **2.2** Transferencia de aprendizaje (transfer learning):
  - Reutilizar la extracción de características de una red preentrenada
  - Congelar la base y entrenar solo la cabeza de clasificación
  - Ejemplo con ResNet50

## Materiales

| Archivo | Descripción |
|---|---|
| `Clase16_M3U2_Residual_networks.pptx` | Presentación académica (12 diapositivas) |
| `01_El_bloque_residual.ipynb` | Notebook 1: bloque residual con la API funcional de Keras |
| `02_Transfer_learning.ipynb` | Notebook 2: transfer learning (demostración + referencia con ResNet50) |

## Cómo usar los notebooks

1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno) o ábrelo desde GitHub.
2. Ejecuta las celdas en orden con **Shift + Enter**.
3. Lee cada celda de texto antes de ejecutar el código que tiene debajo.

Ambos notebooks incluyen la teoría junto a los ejemplos y han sido verificados. En Colab, TensorFlow ya viene instalado.
