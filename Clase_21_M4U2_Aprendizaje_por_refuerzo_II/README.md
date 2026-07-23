# Módulo 4, Unidad 2: Aprendizaje por refuerzo — Parte II

**Introducción al Deep Learning** · Duración aproximada: 75 minutos

Segunda parte de la unidad de aprendizaje por refuerzo: los **algoritmos**. Partiendo del marco de la
Parte I (agente, entorno, MDP, política y valor), aquí el agente **aprende sin conocer el entorno**.

## Contenido de esta clase

- **2.3** Q-Learning:
  - La tabla Q y el aprendizaje sin modelo (model-free)
  - Exploración vs. explotación y la estrategia ε-greedy
  - La regla de actualización: `Q(s,a) ← Q(s,a) + α·[r + γ·max Q(s') − Q(s,a)]`
  - Cómo emerge la política óptima
- **2.4** Deep Q-Networks (DQN):
  - Por qué la tabla no escala (Atari, millones de estados)
  - Sustituir la tabla por una red neuronal que aproxima Q(s, a)
  - Los dos trucos clave: repetición de experiencia y red objetivo

## Materiales

| Archivo | Descripción |
|---|---|
| `Clase21_M4U2_Aprendizaje_por_refuerzo_II.pptx` | Presentación académica (14 diapositivas) |
| `01_Q_Learning_tabular.ipynb` | Notebook 1: Q-Learning tabular — el agente aprende el camino solo (NumPy) |
| `02_Deep_Q_Network.ipynb` | Notebook 2: una DQN con repetición de experiencia y red objetivo (TensorFlow) |

## Cómo usar los notebooks

1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno) o ábrelo desde GitHub.
2. Ejecuta las celdas en orden con **Shift + Enter**.
3. Lee cada celda de texto antes de ejecutar el código que tiene debajo.

Los notebooks incluyen la teoría junto a los ejemplos. El Notebook 1 solo usa NumPy y se ejecuta en
segundos; el Notebook 2 usa TensorFlow y el entrenamiento del DQN tarda un poco (unos segundos por bloque
de episodios). Ambos usan la misma rejilla 4×4 para que se pueda comparar la tabla con la red.
