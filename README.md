# 🎓 ML desde cero — FIND-S y Naive Bayes

Trabajo Práctico de Aprendizaje Automático (UNAHUR) que implementa
dos algoritmos de clasificación desde cero en Python, aplicados a un
dataset de otorgamiento de créditos bancarios.

---

## 📌 ¿Qué hace este proyecto?

### 1. Algoritmo FIND-S
- Filtra el dataset por edad (50 años) y divide en 75% train / 25% test
- Implementa FIND-S desde cero para encontrar la hipótesis más específica
- Predice otorgamiento de crédito en base a: Sexo, Nivel educativo,
  Estado de vivienda y Préstamos previos impagos
- Evalúa con matriz de confusión y métricas completas

### 2. Clasificador Naive Bayes categórico
- Filtra por rango de edad (40-45 años), divide en 80% train / 20% test
- Implementa Naive Bayes desde cero sin usar sklearn
- Calcula probabilidades condicionales P(Xj | Y) para cada atributo
- Evalúa con matriz de confusión y métricas completas

---

## 📊 Métricas calculadas

Accuracy · Recall · Precisión · F1-score · Especificidad · TPR · FPR

---

## 🛠 Tecnologías

- Python · Pandas · NumPy

---

## 🚀 Cómo ejecutarlo

1. Descargá el notebook `Aprendizaje_Automatico_TP_1.ipynb`
2. Subilo a [Google Colab](https://colab.research.google.com)
3. Subí el archivo `Datos.csv` al entorno de Colab
4. Ejecutá las celdas en orden

---

## 📁 Dataset

El dataset contiene registros de solicitudes de crédito bancario con
atributos como edad, sexo, nivel educativo, estado de vivienda y
historial de préstamos. Variable objetivo: `Estado` (OTORGADO / RECHAZADO).
