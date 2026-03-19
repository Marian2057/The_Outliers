**Equipo:** The Outliers 📊 
Integrantes:
* Claudia Metz
* Marianela Pi
**Proyecto:** Trabajo Final Integrador - Modelos Predictivos  

## 🎯 Objetivo del Proyecto
El objetivo de este proyecto es aplicar el ciclo completo de análisis de datos y Machine Learning para predecir la cantidad de siniestros viales en Argentina. Para ello, procesamos datasets públicos y desarrollamos dos modelos predictivos de regresión, evaluando su rendimiento y almacenando todo el ciclo en una base de datos NoSQL. Finalmente, los resultados se exponen de manera interactiva.

## 🛠️ Herramientas y Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Análisis y Manipulación de Datos:** Pandas, NumPy
* **Machine Learning:** Scikit-Learn (Pipelines, Modelos de Regresión)
* **Base de Datos NoSQL:** MongoDB (PyMongo)
* **Visualización:** Streamlit, Matplotlib, Seaborn
* **Control de Versiones:** Git / GitHub

## 🧠 Modelos y Métricas (Scikit-Learn)
Dado que el objetivo requiere el uso de métricas de regresión, se transformó el dataset original para predecir variables continuas (cantidad de siniestros).

Se compararon al menos dos algoritmos de regresión. La evaluación técnica se basó en:
* RMSE (Root Mean Squared Error)
* MAE (Mean Absolute Error)
* R² (Coeficiente de Determinación)

El preprocesamiento (escalado de variables numéricas y codificación de variables categóricas) se integró utilizando Pipelines y ColumnTransformer para garantizar buenas prácticas y evitar el data leakage (fuga de datos).

## 🗄️ Almacenamiento NoSQL
Se implementó una base de datos documental (MongoDB) que contiene tres colecciones principales:
* 1. datos_entrada: Registros del dataset limpio y preprocesado.
* 2. resultados_modelo: Predicciones generadas y métricas obtenidas (RMSE, MAE, R²).
* 3. configuracion: Hiperparámetros y metadatos de los modelos entrenados.

## 📂 Estructura del Repositorio
```text
├── data/
│   ├── siniestros_limpios.csv      # Dataset preprocesado
├── notebooks/
│   ├── 01_ETL_y_EDA.ipynb          # Extracción, limpieza y exploración
│   ├── 02_Modelos_Machine_Learning.ipynb # Entrenamiento y evaluación
├── scripts/
│   ├── db_connection.py            # Script de conexión y carga a MongoDB
├── app.py                          # Aplicación interactiva de Streamlit
├── requirements.txt                # Dependencias del proyecto
└── README.md                       # Documentación



