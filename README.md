# 🚗 Car Price Prediction - Multiple Linear Regression

Este proyecto implementa un análisis de regresión lineal simple para predecir el precio de automóviles utilizando variables técnicas del vehículo. Se trata de un estudio comparativo entre diferentes variables predictoras usando Python y herramientas del ecosistema de ciencia de datos.

---

## 📊 Objetivo

Aplicar modelos de regresión lineal simple sobre tres variables numéricas (`horsepower`, `enginesize`, `curbweight`) para evaluar cuál tiene mayor poder predictivo sobre el precio de un automóvil.

---

## 📁 Dataset

- **Nombre:** CarPrice_Assignment.csv  
- **Fuente:** [Kaggle](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)  
- **Tamaño:** 205 registros, 26 variables  
- **Variables analizadas:**
  - `horsepower`: Caballos de fuerza del motor
  - `enginesize`: Tamaño del motor
  - `curbweight`: Peso del vehículo
  - `price`: Precio del automóvil (variable dependiente)

---

## 🛠️ Tecnologías y Librerías

- Python 3.x
- Jupyter Notebook
- pandas
- matplotlib
- seaborn
- scikit-learn

---

## 📈 Resultados principales

| Modelo                   | R² (Score) | Coeficiente |
|--------------------------|------------|-------------|
| Horsepower vs Price      | 0.6531     | 163.26      |
| Engine Size vs Price     | 0.7641 ✅  | 167.70      |
| Curb Weight vs Price     | 0.6977     | 12.82       |

> El modelo con `enginesize` obtuvo el mejor ajuste lineal, explicando el 76.4% de la variabilidad del precio.

---

## 🧠 Conclusiones

- El tamaño del motor fue el predictor más fuerte del precio.
- Todas las variables analizadas mostraron relaciones lineales positivas con la variable objetivo.
- El análisis refuerza el uso de la regresión lineal como herramienta explicativa inicial en ciencia de datos.

---

## 🚀 Cómo ejecutar el proyecto

1. Clona el repositorio:

```bash
git clone https://github.com/MayChio/Car-Price-Prediction-Multiple-Linear-Regression.git
