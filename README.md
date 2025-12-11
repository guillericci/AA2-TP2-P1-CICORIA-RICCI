# Clasificación de Dígitos hablados (0-9)

## **Descripción:**  

Este proyecto entrena modelos de deep learning para clasificar dígitos hablados del 0 al 9 utilizando espectrogramas generados a partir de clips de audio. El mismo se implemento en **Python** y **Google Colab**.

Se entrenan dos modelos de deep learning, ambos basados en espectrogramas:
  
  - 🟦 **Modelo Convolucional** (CNN)
  
  - 🟩 **Modelo Recurrente** (RNN) basado en secuencias (LSTM / GRU)

---

## **Datasets:** 

🔊 **Spoken Digit — TensorFlow Datasets**

Se utiliza el dataset Spoken Digit de TensorFlow Datasets, compuesto por:

- 3000 audios
- 6 locutores
- 50 muestras por dígito por locutor
- Frecuencia: 8 kHz, mono
- Clips de aproximadamente 1 segundo

El objetivo es entrenar modelos capaces de identificar correctamente qué dígito (0–9) se pronuncia en cada clip.

🎙️**Dataset de Test Propio**

Cada integrante grabó:

- 10 audios → uno por dígito (0–9)
- Sample rate fijado en 8 kHz

Se evaluaron ambos modelos sobre este dataset para medir generalización en voces no vistas.

---

## Ejecución

El desarrollo se realizó en Google Colab.

El notebook incluye:

- Preprocesamiento
- Definición de los modelos
- Entrenamiento
- Evaluaciones
- Testing con audios propios


---

## Tecnologías Utilizadas

- Python 
- TensorFlow / Keras  
- NumPy / Pandas / Matplotlib / Seaborn  

---

## Autores
**Cicoria, Ignacio - Ricci, Guillermo**
