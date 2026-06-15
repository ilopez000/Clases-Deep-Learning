# Clase 8 · Módulo 3, Unidad 3: Redes Generativas Adversarias (GANs)

**Introducción al Deep Learning** · Duración aproximada: 75 minutos

## Contenido de esta clase

- **3.1** Introducción: redes que generan datos nuevos (Goodfellow, 2014) y sus aplicaciones
- **3.2** Cómo funciona una GAN: generador vs. discriminador, la estructura, el juego adversario (minimax, equilibrio de Nash) y las funciones de pérdida (minimax y Wasserstein)
- **3.3** Construcción de una DGAN: arquitectura del generador (Dense, Reshape, Conv2DTranspose, LeakyReLU, BatchNorm) y el bucle de entrenamiento
- **3.4** Tipos de GANs: semisupervisada (SGAN), condicional (cGAN) y CycleGAN

## Materiales

| Archivo | Descripción |
|---|---|
| `Clase08_M3U3_GANs.pptx` | Presentación académica (16 diapositivas) |
| `01_La_idea_adversaria.ipynb` | Notebook 1: una GAN sencilla que aprende una distribución (la mecánica adversaria) |
| `02_Una_DGAN_genera_digitos.ipynb` | Notebook 2: una DGAN que genera imágenes de dígitos |

## Cómo usar los notebooks

1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno) o ábrelo desde GitHub.
2. Ejecuta las celdas en orden con **Shift + Enter**.
3. Lee cada celda de texto antes de ejecutar el código que tiene debajo.

Los notebooks incluyen la teoría junto a los ejemplos. Entrenar una GAN es lento: con más épocas las imágenes mejoran. En Colab, TensorFlow ya viene instalado (y con GPU el entrenamiento es mucho más rápido).
