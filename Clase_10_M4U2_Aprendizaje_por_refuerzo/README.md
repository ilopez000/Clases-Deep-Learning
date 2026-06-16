# Clase 10 · Módulo 4, Unidad 2: Aprendizaje por refuerzo

**Introducción al Deep Learning** · Duración aproximada: 75 minutos

## Contenido de esta clase

- **2.1** Introducción: aprender por prueba y error (inspiración conductista) e hitos (Q-Learning, Atari, AlphaGo)
- **2.2** Aprendizaje por refuerzo: el bucle agente-entorno, el proceso de decisión de Markov (MDP), política, recompensa y factor de descuento, funciones de valor y ecuación de Bellman, y el algoritmo Q-Learning (tabla Q, exploración/explotación)
- **2.3** Deep Reinforcement Learning: el problema del tamaño de la tabla y las Deep Q-Networks (DQN)

## Materiales

| Archivo | Descripción |
|---|---|
| `Clase10_M4U2_Aprendizaje_por_refuerzo.pptx` | Presentación académica (16 diapositivas) |
| `01_Q_Learning_desde_cero.ipynb` | Notebook 1: Q-Learning con tabla en un gridworld (NumPy) |
| `02_Deep_Q_Network_DQN.ipynb` | Notebook 2: una DQN con Keras en el mismo entorno |

## Cómo usar los notebooks

1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno) o ábrelo desde GitHub.
2. Ejecuta las celdas en orden con **Shift + Enter**.
3. Lee cada celda de texto antes de ejecutar el código que tiene debajo.

Ambos notebooks incluyen la teoría junto a los ejemplos. El notebook 01 (Q-Learning) es rápido; el 02 (DQN) entrena una red y es más lento (con GPU en Colab va mucho mejor).
