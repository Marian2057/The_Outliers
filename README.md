**Equipo:** The Outliers 📊  
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



