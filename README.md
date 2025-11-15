# 📊 Adult Census Income — Machine Learning Classification Project

Este repositorio contiene un análisis completo del dataset **Adult / Census Income** del *UCI Machine Learning Repository*.  
El objetivo principal es **predecir si un individuo gana más de 50.000 $ al año**, utilizando técnicas de análisis exploratorio y varios modelos de clasificación.

---

## 📁 Contenido del proyecto

### 🔍 **1. Análisis Exploratorio de Datos (EDA)**
- Inspección de tipos de datos  
- Distribución de variables  
- Detección de valores faltantes y valores especiales (“?”)  
- Análisis bivariante con la variable objetivo `income`

### 🧹 **2. Limpieza y Preprocesamiento**
- Eliminación de espacios y caracteres no deseados  
- Tratamiento de valores perdidos  
- Codificación de variables categóricas (OneHotEncoding)  
- Escalado de variables numéricas  
- División en train/test

### 🤖 **3. Modelado**
Modelos implementados:

- Regresión Logística  
- Árbol de decisión  
- Random Forest (con optimización de hiperparámetros)  
- KNN  
- Naive Bayes  
- SVM  
- Red Neuronal MLP

### 📈 **4. Evaluación**
Métricas analizadas:

- Accuracy  
- Precision, Recall y F1-score  
- Matrices de confusión  
- Comparación final entre modelos

---

## 📦 Dataset

- **Nombre:** Adult / Census Income  
- **Fuente:** UCI Machine Learning Repository  
- **Enlace:** https://archive-beta.ics.uci.edu/dataset/2/adult  
- **Tamaño:** 48.842 filas, 15 columnas  
- **Tarea:** Clasificación binaria (`<=50K` vs `>50K`)

