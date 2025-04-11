# 🏥 Análisis Exploratorio y Predicción de Ingresos en Supermercado Local

Este proyecto presenta un estudio completo de ventas e ingresos en un supermercado minorista simulado con sucursales en tres ciudades ficticias: **Ituzaingó**, **Morón** y **Hurlingham** (Argentina). Incluye análisis exploratorio, visualizaciones, extracción de insights comerciales y una proyección de ingresos mensuales mediante Machine Learning.

---

## 🔄 Tecnologías utilizadas

- Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)
- Google Colab
- Jupyter Notebook
- CSV (fuente: Kaggle - Supermarket Sales)

---

## 🔍 Objetivos del proyecto

- Traducir y adaptar datos a un escenario local (ARS + ciudades reales)
- Realizar un EDA completo con visualizaciones profesionales
- Detectar patrones de venta y rentabilidad
- Predecir ingresos futuros por sucursal usando regresión lineal

---

## 📊 Principales hallazgos

- **Mayor ingreso total**: Sucursal Ituzaingó  
- **Método de pago más frecuente**: Ewallet  
- **Línea de producto más rentable**: Salud y Belleza  
- **Rating promedio**: Parejo entre las tres ciudades, entre 6.5 y 8  
- **Proyección**: Ingresos estimados para el siguiente trimestre, con caídas leves proyectadas  

---

## 🚀 Predicción de ingresos (ML)

Se utilizaron modelos de regresión lineal (uno por ciudad) para proyectar los ingresos de abril, mayo y junio de 2019. Los resultados se integraron al análisis para mostrar continuidad de la tendencia.

> El modelo alcanzó un R² > 0.99 con un RMSE menor a $12.000 ARS, lo que indica un excelente ajuste.

---

## 📁 Estructura del repositorio
```
supermercado_analisis_ingresos/
├── data/
│   └── ventas_supermercado_ARS.csv
├── notebooks/
│   └── supermercado_analisis_ingresos.ipynb
├── images/
│   └── graficos_eda_y_prediccion.png
└── README.md
```
---

## 📂 Dataset original

- Kaggle: [Supermarket Sales Dataset](https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales)

---

## 🙌 Autor

**Juan Ignacio Algarin**  
Estudiante de Ciencia de Datos - UNSAM  
Apasionado por el análisis aplicado, la visualización de datos y la automatización de decisiones comerciales.
