# Clasificaci-n-de-Sentimientos-en-Tweets-usando-BI-LSTM
Realiza un análisis de sentimientos del conjunto tweets_Dataset usando un modelo BI-LSTM. En el ejercicio 1 clasifica tweets en Positivo y Negativo usando TF-IDF y preprocesamiento de texto. En el ejercicio 2 clasifica Positivo, Negativo y Neutro utilizando word embeddings y las técnicas de preprocesamiento que consideres adecuadas.

# Clasificación de Sentimientos con BI-LSTM

## Descripción

En este ejercicio se implementará un sistema de **análisis de sentimientos** utilizando técnicas de **Procesamiento de Lenguaje Natural (NLP)** y **redes neuronales recurrentes**.

Se trabajará con el conjunto de datos **tweets_Dataset**, el cual contiene publicaciones de Twitter etiquetadas según su **polaridad de sentimiento**.

El objetivo es construir modelos de clasificación utilizando **BI-LSTM (Bidirectional Long Short-Term Memory)** para identificar el sentimiento expresado en los textos.

---

## Ejercicio 1

Construye un modelo **BI-LSTM** para clasificar los tweets en **dos categorías**:

- Positivo
- Negativo

Antes de entrenar el modelo, aplica técnicas de **preprocesamiento de texto**, tales como:

- n-gramas
- lematización
- derivación (stemming)
- eliminación de palabras vacías (opcional)

Además, utiliza una técnica de **representación de texto basada en TF-IDF** para transformar los tweets en **vectores numéricos**.

---

## Ejercicio 2

Construye un segundo modelo **BI-LSTM** para clasificar los tweets en **tres categorías**:

- Positivo
- Negativo
- Neutro

En este caso, el preprocesamiento puede incluir:

- n-gramas
- lematización
- derivación
- o ninguno, según tu criterio experimental.

La representación de los textos deberá realizarse utilizando **word embeddings**.

---

## Entregables

Los estudiantes deberán:

- Subir los **notebooks con las implementaciones**.
- Mostrar los **resultados obtenidos**.
- Presentar el **análisis durante la clase**.
