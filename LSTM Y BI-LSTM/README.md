# Clasificación de Sentimientos con BI-LSTM

Este proyecto implementa modelos de análisis de sentimientos en tweets utilizando redes neuronales BI-LSTM y técnicas de Procesamiento de Lenguaje Natural (NLP).

El código fue desarrollado como parte de una práctica académica para explorar diferentes técnicas de representación de texto y su impacto en modelos de aprendizaje profundo.

Se utilizan dos enfoques principales:

- Representación basada en **TF-IDF**
- Representación basada en **Word Embeddings**

El objetivo es clasificar tweets según su polaridad de sentimiento.

---

# Estructura del Proyecto

```
.
├── Clasificación con LSTM_TF-IDF.ipynb
├── Clasificacion con LSTM_EMBEDDING.ipynb
├── tweets_Dataset.csv
└── README.md
```

---

# Tecnologías Utilizadas

- Python
- PyTorch
- Scikit-learn
- NLTK
- SpaCy
- NumPy
- Matplotlib
- Gensim

---

# Dataset

Se utiliza el conjunto de datos **tweets_Dataset**, que contiene publicaciones de Twitter etiquetadas según su sentimiento.

Las etiquetas consideradas son:

- Positivo
- Negativo
- Neutro

---

# Preprocesamiento de Texto

Antes de entrenar los modelos se aplican diferentes técnicas de procesamiento de texto, como:

- Conversión a minúsculas
- Eliminación de caracteres especiales
- Eliminación de stopwords
- Lematización
- Generación de n-gramas
- Normalización del texto

---

# Modelos Implementados

## BI-LSTM con TF-IDF

Archivo:

```
Clasificación con LSTM_TF-IDF.ipynb
```

Características:

- Representación del texto utilizando TF-IDF
- Clasificación binaria:
  - Positivo
  - Negativo
- Entrenamiento de un modelo Bidirectional LSTM

---

## BI-LSTM con Word Embeddings

Archivo:

```
Clasificacion con LSTM_EMBEDDING.ipynb
```

Características:

- Representación del texto mediante Word Embeddings
- Clasificación multiclase:
  - Positivo
  - Negativo
  - Neutro
- Uso de una arquitectura Bidirectional LSTM para capturar contexto en ambas direcciones

---

# Ejecución

1. Instalar dependencias

```bash
pip install torch numpy pandas scikit-learn nltk spacy matplotlib gensim
```

2. Descargar recursos necesarios de NLTK

```python
import nltk
nltk.download('stopwords')
nltk.download('punkt')
```

3. Ejecutar los notebooks utilizando Jupyter

```bash
jupyter notebook
```

