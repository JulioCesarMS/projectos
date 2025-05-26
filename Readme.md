# 📊 Análisis de Clientes con Tarjeta de Crédito - Default Prediction

Este proyecto explora y analiza un conjunto de datos de clientes con tarjeta de crédito en Taiwán. El objetivo principal es comprender las características de los clientes y predecir el monto del pago realizado en el mes de junio (`PAY_AMT4`), evitando el uso de variables futuras que puedan generar "data leakage".

---

## 📁 Descripción de los Datos

El dataset contiene información de 30,000 clientes, incluyendo variables demográficas, historial de pagos, montos facturados y pagos realizados entre abril y septiembre de 2005. Algunas variables clave son:

- `LIMIT_BAL`: Crédito otorgado en dólares NT.
- `SEX`, `EDUCATION`, `MARRIAGE`, `AGE`: Variables demográficas.
- `PAY_0` a `PAY_6`: Estado de pagos mensuales (retrasos, pagos puntuales).
- `BILL_AMT1` a `BILL_AMT6`: Monto de la factura mensual.
- `PAY_AMT1` a `PAY_AMT6`: Pagos realizados mensualmente.
- `default payment next month`: Variable objetivo para clasificación (1 = default, 0 = no default).

---

## 🔍 Objetivo del Análisis

En este proyecto se busca:
1. Realizar un análisis exploratorio profundo del dataset.
2. Visualizar el desbalance de clases en la variable `default payment next month`.
3. Predecir el monto de pago realizado en junio (`PAY_AMT4`) utilizando únicamente variables de meses anteriores.
4. Evitar el uso de variables futuras para prevenir *data leakage*.
5. Estudiar relaciones entre variables socioeconómicas y comportamiento de pago.

---

## 🛠️ Herramientas utilizadas

- `Python` 3.11.7
- `Pandas`, `NumPy` para manipulación de datos.
- `Matplotlib`, `Seaborn` para visualización.
- `Jupyter Notebook` para análisis interactivo.

---


---

## 📁 Estructura del repositorio


---
