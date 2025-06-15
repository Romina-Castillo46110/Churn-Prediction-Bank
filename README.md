# 🏦 Churn Prediction - Análisis Exploratorio de Datos

## 📊 Descripción del Dataset

El dataset contiene información sobre más de **10.000 clientes**, incluyendo:

- Datos demográficos: edad, género, país de residencia
- Datos financieros: balance en cuenta, ingresos, productos contratados
- Variables comportamentales: actividad reciente, tarjeta de crédito, etc.
- Variable objetivo: `Exited` (1 si el cliente se fue, 0 si permanece)

## 🎯 Objetivo

Identificar los factores que más influyen en la decisión de un cliente de abandonar el banco, mediante un **análisis exploratorio de datos (EDA)** que siente las bases para una futura etapa de modelado predictivo.

---

## 🔍 Etapas del análisis

### 1. Carga y descripción inicial del dataset
- Lectura del archivo CSV (`Churn_Modelling.csv`)
- Verificación del tipo de datos
- Análisis de valores faltantes

### 2. Análisis univariado
- Histogramas y gráficos de distribución para variables como edad, balance, ingresos
- Análisis de frecuencia de la variable objetivo (`Exited`)

### 3. Análisis bivariado
- Comparación entre clientes que se fueron y los que permanecieron según edad, país y productos contratados
- Gráficos de barras y boxplots segmentados por churn

### 4. Análisis multivariado
- Correlaciones entre variables numéricas
- Mapas de calor (heatmaps)
- Gráficos de dispersión diferenciando por clase (`Exited`)

---

## 📁 Estructura del repositorio

```text
📂 churn-prediction/
 ┣ 📜 ProyectoDSParteI_Castillo.ipynb   → Notebook con el análisis
 ┣ 📜 README.md                         → Este archivo
 ┗ 📜 Churn_Modelling.csv              → Dataset original
```

---

## 🛠 Tecnologías utilizadas

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 👤 Autor/a

Romina Castillo - Data Scientist en formación

---
















