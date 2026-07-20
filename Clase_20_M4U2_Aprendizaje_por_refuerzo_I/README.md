# Módulo 4, Unidad 2: Aprendizaje por refuerzo — Parte I

**Introducción al Deep Learning** · Duración aproximada: 75 minutos

Primera parte de la unidad de aprendizaje por refuerzo: el **marco conceptual**. Los algoritmos
(Q-Learning y DQN) se ven en la Parte II.

## Contenido de esta clase

- **2.1** Introducción: aprender por prueba y error; hitos (Q-Learning 1992, Atari 2015, AlphaGo 2016); diferencias con el aprendizaje supervisado y no supervisado
- **2.2** El marco del refuerzo:
  - El bucle agente – entorno
  - Los cinco elementos: agente, entorno, estado, acción y refuerzo
  - El proceso de decisión de Markov (MDP) y el POMDP
  - La política π, la recompensa y el factor de descuento γ
  - Las funciones de valor V(s) y Q(s, a)
  - La ecuación de Bellman

## Materiales

| Archivo | Descripción |
|---|---|
| `Clase20_M4U2_Aprendizaje_por_refuerzo_I.pptx` | Presentación académica (15 diapositivas) |
| `01_Un_entorno_de_refuerzo_desde_cero.ipynb` | Notebook 1: entorno, agente aleatorio vs. política, factor γ |
| `02_Valor_de_los_estados_y_Bellman.ipynb` | Notebook 2: V(s), Q(s,a) y evaluación de la política con Bellman |

## Cómo usar los notebooks

1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno) o ábrelo desde GitHub.
2. Ejecuta las celdas en orden con **Shift + Enter**.
3. Lee cada celda de texto antes de ejecutar el código que tiene debajo.

Los notebooks incluyen la teoría junto a los ejemplos. Solo usan **NumPy y Matplotlib** (sin librerías de
RL), para que se vea con claridad qué hace cada pieza del bucle; se ejecutan en segundos.
