Alumno: Koller Tomas, a2011

Este repositorio contiene los cuatro desafíos prácticos realizados durante la materia Procesamiento de Lenguaje Natural. Cada notebook aborda un conjunto de técnicas fundamentales del PLN, con el objetivo de aplicar conceptos teóricos, analizar resultados y reflexionar sobre el comportamiento de los modelos.

A lo largo de estos trabajos se exploraron métodos clásicos de representación, modelos probabilísticos, embeddings, modelos basados en redes neuronales recurrentes y sistemas seq2seq para traducción automática. El foco estuvo siempre en experimentar, interpretar resultados, comparar estrategias y entender las limitaciones reales de cada enfoque.

Desafío 1 — Representación vectorial clásica y clasificación
En este primer desafío se trabajó con vectorización de texto, mediciones de similaridad y modelos de clasificación basados en representaciones simples.

Temas abordados

TF-IDF / Bag of Words: vectorización de documentos.

Cálculo de similaridad (coseno) entre documentos.

Análisis manual de si la similaridad tiene sentido semántico y coincide con etiquetas.

Clasificación por prototipos: asignar la clase del documento más similar.

Modelos Naïve Bayes (Multinomial y ComplementNB) ajustando hiperparámetros.

Transposición para obtener matriz término-documento y estudiar similaridad entre palabras.

Desafío 2 — Creación de embeddings con Gensim
Este desafío introduce embeddings distribucionales entrenados desde cero usando Word2Vec (Gensim) sobre letras de canciones del dataset Songs.

Temas abordados

Entrenamiento de modelos Skip-gram / CBOW.

Exploración de palabras más y menos similares a términos elegidos.

Reducción de dimensionalidad (PCA / TSNE / UMAP) a 2D.

Construcción de visualizaciones y detección de clusters semánticos.

Desafío 3 — Modelos de Lenguaje con RNN, LSTM y GRU
En este desafio se construyeron modelos de lenguaje entrenados desde cero, trabajando con corpus propio y probando distintas unidades recurrentes.

Temas abordados

*Selección y tokenización de corpus.

Generación del dataset tipo “secuencia de entrada → siguiente token”.

Arquitecturas con SimpleRNN, LSTM y GRU.

Entrenamiento guiado por perplejidad.

Generación de texto con:

*Greedy search

*Beam search determinístico

Beam search estocástico + temperatura
Desafío 4 — Traducción automática con modelos seq2seq (PyTorch)
El último desafío consistió en replicar y extender un modelo seq2seq para traducción, empleando embeddings y capas recurrentes en PyTorch.

Temas abordados

Implementación desde cero de un modelo encoder-decoder.

Extensión del dataset y aumento del largo de las sequencias.

Experimentos con distinta cantidad de neuronas en las capas recurrentes.

Generación y análisis de traducciones de ejemplo.
