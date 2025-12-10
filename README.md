Alumno: Koller Tomas, a2011

Este repositorio reúne los cuatro desafíos prácticos desarrollados durante la cursada de Procesamiento de Lenguaje Natural (PLN). Cada notebook introduce y pone en práctica distintos métodos esenciales del área, con la intención de aplicar teoría, analizar comportamientos y obtener una comprensión más profunda del funcionamiento real de los modelos.

A lo largo de los trabajos se investigaron enfoques clásicos de representación, modelos probabilísticos, embeddings distribucionales, arquitecturas basadas en redes neuronales recurrentes y sistemas seq2seq orientados a tareas de traducción automática. El eje principal fue siempre experimentar, interpretar resultados, comparar alternativas y evaluar las limitaciones de cada técnica.

Desafío 1 — Representación vectorial tradicional y clasificación

En este primer desafío se exploraron técnicas básicas de vectorización y modelos simples de clasificación, junto con el análisis de similaridad entre documentos.

Contenido trabajado:

Representación de texto mediante TF-IDF y Bag of Words.

Cálculo de similaridad coseno entre pares de documentos.

Evaluación manual de si la similaridad refleja relaciones semánticas reales.

Clasificación por prototipos asignando la categoría del documento más cercano.

Modelos de Naïve Bayes (Multinomial y ComplementNB) y ajuste de hiperparámetros.

Construcción de la matriz término-documento para estudiar similaridades entre palabras.

Desafío 2 — Entrenamiento de embeddings con Gensim

En este desafío se trabajó con modelos distribucionales entrenados desde cero, utilizando Word2Vec (Gensim) sobre letras de canciones del dataset Songs.

Contenido trabajado:

Entrenamiento de modelos Skip-gram y CBOW.

Inspección de palabras más y menos similares a términos específicos.

Aplicación de técnicas de reducción de dimensionalidad (PCA, t-SNE, UMAP) para visualización en 2D.

Detección de grupos semánticos mediante gráficos y análisis exploratorio.

Desafío 3 — Modelos de Lenguaje con RNN, LSTM y GRU

Este desafío consistió en construir modelos de lenguaje desde cero utilizando diferentes tipos de unidades recurrentes.

Contenido trabajado:

Selección del corpus y proceso de tokenización.

Generación del dataset en formato secuencia → token siguiente.

Diseño de modelos con SimpleRNN, LSTM y GRU.

Entrenamiento supervisado mediante perplejidad.

Generación de texto con:

Greedy search

Beam search determinístico

Beam search estocástico combinado con temperatura

Desafío 4 — Traducción automática con modelos seq2seq en PyTorch

El último trabajo se enfocó en reproducir y mejorar un modelo encoder–decoder para realizar traducción automática, empleando embeddings y capas recurrentes implementadas en PyTorch.

Contenido trabajado:

Implementación completa de un modelo seq2seq desde cero.

Ampliación del conjunto de datos y manejo de secuencias más largas.

Pruebas con distintas cantidades de neuronas en las capas recurrentes.

Generación de traducciones de prueba y análisis cualitativo de sus resultados.
