# Módulo 3, Unidad 3: Redes Generativas Adversarias (GANs) — Parte I

**Introducción al Deep Learning** · Duración aproximada: 75 minutos

Primera parte de la unidad de GANs: **la idea y la mecánica adversaria** (la construcción de una DGAN de imágenes y los tipos de GAN se ven en la Parte II).

## Contenido de esta clase

- **3.1** Introducción: redes que generan datos nuevos (Goodfellow, 2014) y sus aplicaciones
- **3.2** Cómo funciona una GAN: generador vs. discriminador, la estructura de la red, el juego adversario (minimax, equilibrio de Nash) y las funciones de pérdida (minimax y Wasserstein)

## Materiales

| Archivo | Descripción |
|---|---|
| `Clase17_M3U3_GANs_I.pptx` | Presentación académica (13 diapositivas) |
| `01_La_idea_adversaria.ipynb` | Notebook 1: una GAN sencilla que aprende una distribución (1D) |
| `02_Una_GAN_2D.ipynb` | Notebook 2: una GAN que aprende una nube de puntos (un anillo, 2D) |

## Cómo usar los notebooks

1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno) o ábrelo desde GitHub.
2. Ejecuta las celdas en orden con **Shift + Enter**.
3. Lee cada celda de texto antes de ejecutar el código que tiene debajo.

Los notebooks incluyen la teoría junto a los ejemplos. Entrenar una GAN es delicado; con más pasos los resultados mejoran. En Colab, TensorFlow ya viene instalado.
