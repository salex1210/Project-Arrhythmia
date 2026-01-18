
# Cardiac Arrhythmia Classification using Deep Learning

## Introduction to Deep Learning 2024-2

Este proyecto tiene como objetivo desarrollar un modelo de **Deep Learning** capaz de clasificar distintos tipos de **arritmias cardíacas** a partir de señales de electrocardiograma (ECG), utilizando técnicas modernas de aprendizaje profundo y procesamiento de datos biomédicos.

El trabajo fue realizado como parte del curso **Introduction to Deep Learning (2024-2)**.

---

## Project Description

Las arritmias cardíacas representan una de las principales causas de enfermedades cardiovasculares. El análisis automático de señales ECG mediante redes neuronales permite apoyar el diagnóstico clínico y reducir errores humanos.

En este proyecto se implementa un modelo de clasificación que:

- Procesa datos de ECG previamente etiquetados.
- Entrena una red neuronal profunda.
- Evalúa el desempeño del modelo mediante métricas de clasificación.
- Analiza la precisión obtenida sobre el conjunto de prueba.

---

## Dataset

El conjunto de datos corresponde a registros de señales ECG asociados a diferentes clases de arritmia cardíaca.

Características generales:

- Señales preprocesadas y normalizadas.
- Datos divididos en entrenamiento y prueba.
- Etiquetas correspondientes a distintos tipos de latidos cardíacos.

> El dataset fue suministrado a través del aula virtual del curso.

---

## Methodology

El flujo de trabajo del proyecto es el siguiente:

1. **Carga de datos**
   - Importación del dataset.
   - Separación de variables de entrada y etiquetas.

2. **Preprocesamiento**
   - Normalización de las señales.
   - Conversión de etiquetas a formato categórico.
   - División entrenamiento / validación.

3. **Model Architecture**
   - Red neuronal profunda basada en:
     - Capas densas (Dense)
     - Funciones de activación ReLU
     - Capa de salida Softmax
   - Optimización mediante Adam.

4. **Training**
   - Entrenamiento del modelo durante múltiples épocas.
   - Monitoreo de pérdida y precisión.

5. **Evaluation**
   - Evaluación del modelo con datos de prueba.
   - Obtención de la exactitud (accuracy).

---

## Technologies Used

- **Python 3**
- **TensorFlow / Keras**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Jupyter Notebook**

---

## Results

El modelo entrenado alcanza una precisión adecuada para la clasificación de arritmias cardíacas.

La métrica de **accuracy final** se encuentra registrada directamente en el notebook:


## Dataset

Los datos utilizados en este proyecto no se incluyen en el repositorio
debido a restricciones de tamaño de GitHub.

Pueden descargarse desde:

[https://drive.google.com/xxxxx
](https://drive.google.com/drive/folders/199fls6GPwJMOkrEvnkfBpgcnEFL2Eoj6)

Archivos:

- training_set_500.h5
- test_without_labels_200.h5

Una vez descargados, deben ubicarse en la carpeta:

data/

