# 📡 Telecom X: Predicción de Fuga de Clientes (Churn Analysis)

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)
![Status](https://img.shields.io/badge/Status-Completado-green.svg)

## 📝 Descripción del Proyecto
Este proyecto desarrolla un sistema de **Inteligencia Artificial** capaz de predecir qué clientes tienen una alta probabilidad de abandonar los servicios de la empresa **Telecom X**. 

A diferencia de un análisis reactivo, este modelo permite a la compañía identificar patrones de comportamiento (como tipos de contrato y cargos mensuales) antes de que el cliente cancele el servicio, permitiendo ejecutar estrategias de retención proactivas.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python 3.x
* **Librerías Principales:** * `Pandas` & `NumPy`: Manipulación de datos.
    * `Scikit-Learn`: Modelado de Machine Learning.
    * `Imbalanced-learn (SMOTE)`: Balanceo de clases.
    * `Matplotlib` & `Seaborn`: Visualización de datos.
* **Entorno:** Google Colab / Jupyter Notebook.

## 🧠 Metodología y Pipeline
El proyecto sigue un flujo de trabajo de Ciencia de Datos de extremo a extremo:



1.  **Limpieza de Datos:** Tratamiento de nulos y eliminación de variables irrelevantes.
2.  **Ingeniería de Características:** Transformación de variables categóricas (Encoding) y estandarización de escalas (`StandardScaler`).
3.  **Balanceo de Datos:** Implementación de **SMOTE** para equilibrar la muestra de clientes que cancelan (clase minoritaria).
4.  **Modelado:** Entrenamiento comparativo entre **Regresión Logística** y **Random Forest**.
5.  **Evaluación:** Auditoría mediante Matrices de Confusión, Recall, F1-Score y análisis de Overfitting.

## 📊 Hallazgos Clave
* **Contratos:** El contrato "Mes a Mes" es el predictor #1 de fuga.
* **Antigüedad:** Los primeros 6 meses representan la "zona crítica" de abandono.
* **Modelo Ganador:** El **Random Forest** alcanzó un desempeño superior al 82% de precisión, con un alto enfoque en el **Recall** para minimizar las fugas no detectadas.



## 🚀 Instalación y Uso
Para ejecutar este proyecto localmente o en la nube:

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/jfacabreran/TelecomX-Churn-Prediction.git]

## 🚀 Instalación y Uso
Para ejecutar este proyecto localmente o en la nube:

2. Instalar dependencias:
pip install pandas scikit-learn matplotlib seaborn imbalanced-learn

3. Ejecución:
Abre el archivo TelecomX_LATAM_2.ipynb en Google Colab o Jupyter y ejecuta todas las celdas. El dataset se consume automáticamente desde la nube para garantizar la reproducibilidad.

💡 Estrategias Sugeridas para Negocio
Basado en el modelo, se proponen 3 ejes de acción:

Campaña de Migración: Incentivos para pasar de planes mensuales a anuales.

Programa Welcome Care: Contacto preventivo en el mes 2 de antigüedad.

Optimización de Planes: Ajustes proactivos en clientes con cargos elevados.

✒️ Autor
Juan Fernando Antonio Cabrera Nava - https://www.linkedin.com/in/jfacabreran/ - https://github.com/jfacabreran