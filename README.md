# Desafíos de Procesamiento de Lenguaje Natural (PLN)

Este repositorio contiene una serie de desafíos realizados para explorar diferentes técnicas y modelos en el campo del Procesamiento de Lenguaje Natural (PLN). A continuación, se describe cada desafío en detalle.

## Desafío 1: Vectorización de Documentos y Modelos Naive Bayes

En este desafío, se abordó la vectorización de documentos y se entrenaron diferentes modelos de Naive Bayes, incluyendo Naive Bayes Multinomial y Bernoulli. Se realizó una primera aproximación a embeddings mediante la transposición de la matriz documento-término utilizando el dataset `fetch_20newsgroups`.

**Archivos relevantes:**
- `Desafio1_PNL.ipynb`
- `requirements.txt`
- `README`

## Desafío 2: Uso de Embeddings con Word2Vec

Este desafío se centró en la utilización de embeddings con Word2Vec, empleando tanto Skip-gram como CBOW. Se realizaron pruebas de similitudes y analogías en el espacio de embedding. Además, se visualizó el espacio de embedding en TensorFlow Projector mediante técnicas de reducción de dimensionalidad como PCA y t-SNE. Se utilizó un corpus de historias de superhéroes de Marvel, generado mediante prompts a un modelo de lenguaje grande (LLM).

**Archivos relevantes:**
- `Desafio2_PNL.ipynb`
- `requirements.txt`
- `README`

## Desafío 3: Generación de Modelos de Lenguaje con Redes Neuronales Recurrentes

En este desafío, se exploraron diferentes unidades recurrentes (SimpleRNN, LSTM, GRU) para la generación de modelos de lenguaje. Se aplicaron estrategias de búsqueda Greedy y Beam, tanto de manera determinística como estocástica, utilizando temperaturas ajustables. El corpus utilizado fue el mismo de historias de superhéroes de Marvel del Desafío 2.

**Archivos relevantes:**
- `Desafio3_PNL.ipynb`
- `requirements.txt`
- `README`

## Desafío 4: Construcción de un BOT con Embeddings Preentrenados

Aquí se desarrolló un BOT capaz de responder preguntas utilizando embeddings preentrenados de GloVe en inglés. El BOT se basó en una arquitectura Encoder-Decoder con unidades recurrentes LSTM. El dataset utilizado fue `data_volunteers.json`.

**Archivos relevantes:**
- `Desafio4.ipynb`
- `requirements.txt`
- `README`

## Desafío 5: Análisis de Sentimiento con Transfer Learning usando BERT

Este desafío consistió en realizar un análisis de sentimiento aplicando transfer learning con el modelo BERT Base. El dataset estaba compuesto por reseñas de usuarios sobre aplicaciones. Se aplicaron dos estrategias principales: la primera fue transformar la variable `score` en `sentiment` debido al desbalanceo del dataset, y la segunda fue utilizar la variable `score` como target. En el enfoque de target `sentiment` se realizaron dos approachs una que fue un transfer learning con feature extraction y en la otra fine tuning.

**Spoiler alert:** Los mejores resultados se encontraron aplicando fine tuning

**Archivos relevantes:**
- `Desafio5_PNL.ipynb`
- `Desafio5_PNL_5classes.ipynb`
- `Desafio5_finetuningPNL.ipynb`
- `requirements.txt`
- `README`



