# 📊 Análisis de Evasión de Clientes (Churn) - Desafío 2 LATAM

Este proyecto forma parte del **Challenge 2 de la Especialización en Data Science - Alura LATAM**. Su objetivo es analizar los datos de clientes de una empresa de telecomunicaciones ficticia (TelecomX) para identificar patrones de evasión (churn) y proponer estrategias de retención.

---

## 🎯 Objetivo del Proyecto

Analizar el comportamiento de los clientes y detectar características asociadas con la cancelación del servicio. Esto permitirá:

- Entender los factores que impulsan la evasión.
- Identificar perfiles de clientes con mayor riesgo.
- Sugerir estrategias para mejorar la retención.

---

## 🧹 Limpieza y Tratamiento de Datos

Se realizaron los siguientes pasos:

- Carga y normalización de un archivo `.json` con datos anidados.
- Conversión de tipos de datos para facilitar el análisis.
- Revisión de valores faltantes, duplicados y formatos inconsistentes.
- Creación de nuevas variables como `Cuentas_Diarias` para enriquecer el análisis.

---

## 📈 Análisis Exploratorio de Datos (EDA)

Se exploraron variables categóricas y numéricas en relación con la evasión. Esto incluyó:

- Distribución de la variable `Churn`.
- Comparación de evasión por género, contrato, métodos de pago.
- Boxplots para comparar valores monetarios entre clientes que permanecen y los que se van.
- Matriz de correlación para detectar relaciones significativas.

---

## 💡 Conclusiones Principales

- Los contratos mensuales tienen mayor tasa de evasión.
- Métodos de pago electrónicos están más asociados al churn.
- Clientes con menos tiempo de permanencia y menor gasto total tienden a cancelar más.
- Algunos servicios como soporte técnico o protección de dispositivos tienen correlación con la permanencia.

---

## ✅ Recomendaciones Estratégicas

- Incentivar contratos anuales con beneficios adicionales.
- Fortalecer el servicio de atención técnica.
- Implementar alertas tempranas para clientes con bajo gasto y poco tiempo de permanencia.
- Mejorar el seguimiento a los usuarios que usan pagos electrónicos.

---

## 🛠️ Herramientas y Librerías Utilizadas

- Python
- Pandas
- Seaborn
- Matplotlib
- Jupyter Notebook
- Git / GitHub

---

## 📂 Estructura del Proyecto

challenge2-data-science-LATAM/
└── README.md # Este archivo
├── TelecomX_Data.json # Archivo de datos
└── TelecomX_diccionario.md # Diccionario de datos
├── TelecomXEDA.ipynb 
---