# Módulo 3, Unidad 3: Redes Generativas Adversarias (GANs) — Parte II

**Introducción al Deep Learning** · Duración aproximada: 75 minutos

Segunda parte de la unidad de GANs: el salto a las **imágenes** y las variantes de GAN.

## Contenido de esta clase

- **3.3** Construir una DGAN:
  - De ruido a imagen con `Conv2DTranspose` (convolución transpuesta)
  - La red generadora (Dense → Reshape → Conv2DTranspose → LeakyReLU → BatchNorm) y la discriminadora (CNN binaria)
  - El bucle de entrenamiento adversario y las dificultades (equilibrio, colapso de modo)
- **3.4** Tipos de GANs: semisupervisada (SGAN), condicional (cGAN) y CycleGAN

## Materiales

| Archivo | Descripción |
|---|---|
| `Clase18_M3U3_GANs_II.pptx` | Presentación académica (14 diapositivas) |
| `01_Una_DGAN_genera_digitos.ipynb` | Notebook 1: una DGAN que genera imágenes de dígitos |
| `02_GAN_condicional.ipynb` | Notebook 2: una GAN condicional (cGAN) que genera el dígito que le pidas |

## Cómo usar los notebooks

1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno) o ábrelo desde GitHub.
2. Ejecuta las celdas en orden con **Shift + Enter**.
3. Lee cada celda de texto antes de ejecutar el código que tiene debajo.

Los notebooks incluyen la teoría junto a los ejemplos. Entrenar una GAN es lento: con más épocas (y GPU en Colab) las imágenes mejoran notablemente.
