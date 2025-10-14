# 📈 ESTADÍSTICA CON PYTHON: FRECUENCIA Y MEDIDAS DE TENDENCIA CENTRAL

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)

Este proyecto es la **Parte 1** de un curso de **Estadística con Python**. Se enfoca en la introducción a los conceptos estadísticos fundamentales, incluyendo el **análisis de frecuencia** y el cálculo de las principales **medidas de tendencia central y dispersión** utilizando la librería Pandas.

---

## 🧠 Contenido del Proyecto

### 1️⃣ Exploración y Conocimiento de los Datos
- **Dataset:** Se utiliza una muestra de domicilios de Colombia del 2018 (datos didácticos) para el análisis.
- **Variables Clave:** Las variables utilizadas para la exploración incluyen:
    * **Ingreso:** Cuánto gana una persona (variable numérica).
    * **Edad:** Edad de la persona (variable numérica).
    * **Altura:** Altura de la persona (variable numérica).

### 2️⃣ Análisis de Frecuencias
- **Distribución de Frecuencias:** Se demuestra cómo calcular la **frecuencia absoluta** (cantidad de veces que ocurre un valor) para variables categóricas o discretas (ej. Sexo).
- **Frecuencia Relativa:** Se calcula la frecuencia relativa (proporción de cada valor) y se utiliza para construir **tablas de frecuencias**.
- **Visualización de Frecuencias:** Se utiliza la función **`.value_counts()`** de Pandas para obtener rápidamente la distribución de frecuencias.

### 3️⃣ Medidas de Tendencia Central y Dispersión
El proyecto se centra en la aplicación práctica de las siguientes métricas con Python:

| Tipo de Medida | Métrica | Descripción | Función de Pandas/NumPy |
|:---:|:---:|:---:|:---:|
| **Tendencia Central** | **Media (Promedio)** | Valor promedio de un conjunto de datos. | `.mean()` |
| **Tendencia Central** | **Mediana** | El valor central de un conjunto de datos ordenado. | `.median()` |
| **Tendencia Central** | **Moda** | El valor que aparece con más frecuencia. | `.mode()` |
| **Dispersión** | **Desviación Estándar** | Mide cuánto se dispersan los datos con respecto a la media. | `.std()` |
| **Separación** | **Cuartiles** | Puntos que dividen la distribución de datos en cuatro partes. | `.quantile()` |

- **Análisis Segmentado:** Se muestra cómo aplicar estas métricas a **subgrupos** de datos utilizando `.groupby()`, como calcular la desviación estándar de la `Edad` solo para las mujeres.

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Pandas**     | Carga de datos, cálculo de medidas de frecuencia (`.value_counts()`) y medidas descriptivas (`.mean()`, `.std()`, etc.)|
| **NumPy**      | Operaciones numéricas subyacentes (inferido) |

---

## 🎯 Objetivo del Proyecto
Proporcionar una comprensión práctica de la **Estadística Descriptiva** mediante la implementación de Python y Pandas. El objetivo es que el usuario pueda calcular y **analizar las distribuciones de frecuencia** y las principales **medidas de tendencia central y dispersión** en un conjunto de datos real.

---

## 📈 Resultados Clave
- Se demuestra la facilidad de **crear tablas de frecuencia** utilizando métodos nativos de Pandas.
- Se obtienen las métricas descriptivas clave (`Media`, `Mediana`, `Moda`, `Desviación Estándar`) para variables numéricas.
- El proyecto sirve como una base para el **Análisis Exploratorio de Datos (EDA)**, esencial antes de cualquier modelado de Machine Learning.



