# Clase 19 · Módulo 4, Unidad 1: Redes de neuronas recurrentes — Parte I

**Introducción al Deep Learning** · Duración aproximada: 75 minutos

Primera parte de la unidad de redes recurrentes: **por qué el orden importa** y **la memoria** en las redes de neuronas. Cerramos el Módulo 3 (GANs) la clase anterior; aquí abrimos el Módulo 4.

## Contenido de esta clase

- **1.1** Datos secuenciales: cuándo y por qué el orden importa (lenguaje, series temporales, música).
- **1.2** Procesamiento del lenguaje natural (NLP): NLU/NLG y **representación del texto** (tokenización, one-hot/Bag of Words, embeddings y word2vec).
- **1.3** Redes de neuronas recurrentes:
  - La neurona recurrente y el **estado oculto** (la memoria).
  - Configuraciones de entrada/salida (muchos-a-uno, uno-a-muchos, seq2seq).
  - El problema del **gradiente que se desvanece**.
  - **LSTM** y **GRU**: memoria con puertas.

> La atención, los transformers y el análisis de sentimiento se ven en la **Parte II**.

## Materiales

| Archivo | Descripción |
|---|---|
| `Clase19_M4U1_Redes_recurrentes_I.pptx` | Presentación académica (15 diapositivas) |
| `01_Del_texto_a_los_numeros.ipynb` | Notebook 1: tokenización, Bag of Words y embeddings |
| `02_La_neurona_recurrente.ipynb` | Notebook 2: una tarea que depende del orden — red densa vs. SimpleRNN, LSTM y GRU |

## Cómo usar los notebooks

1. Sube el archivo `.ipynb` a [Google Colab](https://colab.research.google.com) (Archivo → Subir cuaderno) o ábrelo desde GitHub.
2. Ejecuta las celdas en orden con **Shift + Enter**.
3. Lee cada celda de texto antes de ejecutar el código que tiene debajo.

Ambos notebooks incluyen la teoría junto a los ejemplos y han sido ejecutados de principio a fin sin errores. En Colab, TensorFlow ya viene instalado.
