# TELECOM-X-CHALLENGE

Telecom X Churn Analysis

Este repositorio contiene el análisis completo del proyecto de evasión de clientes (Churn) para Telecom X. A continuación encuentras la descripción del propósito, la organización de archivos, ejemplos de visualizaciones e instrucciones para ejecutar el análisis.

⸻

📋 Propósito del Análisis

El objetivo de este proyecto es:
	•	Cuantificar la tasa global de churn en la base de clientes de Telecom X.
	•	Explorar patrones de evasión por segmentos demográficos, tipo de contrato y comportamiento de uso.
	•	Identificar variables numéricas y categóricas asociadas a una mayor probabilidad de cancelación.
	•	Proporcionar insights y recomendaciones para reducir la pérdida de clientes.

⸻

🔧 Estructura del Proyecto

TelecomX_Project/
├── data/
│   ├── TelecomX_Data.json       # Datos crudos originales
│   └── TelecomX_diccionario.md  # Diccionario de variables
│
├── notebooks/
│   └── TelecomX_LATAM.ipynb     # Notebook con ETL, EDA y visualizaciones
│
├── README.md                    # Este archivo
└── requirements.txt             # Dependencias de Python

	•	data/: carpeta con los archivos de entrada (JSON y diccionario).
	•	notebooks/: contiene el notebook principal con todo el flujo de trabajo.
	•	requirements.txt: lista de librerías necesarias (pandas, numpy, matplotlib, seaborn, etc.).

⸻

📈 Ejemplos de Gráficos e Insights
	1.	Distribución de Churn

	•	~27% de los clientes se dieron de baja.

	2.	Tasa de Churn por Tipo de Contrato

	•	Contratos mes a mes presentan hasta 15 puntos porcentuales más churn.

	3.	Distribución de Tenure vs. Churn

	•	Clientes con <6 meses y >60 meses muestran mayores niveles de evasión.

⸻

🚀 Instrucciones para Ejecutar el Notebook
	1.	Clonar el repositorio

git clone https://github.com/tu-usuario/TelecomX_Project.git
cd TelecomX_Project


	2.	Instalar dependencias

pip install -r requirements.txt


	3.	Abrir el notebook en Jupyter/Colab
	•	En Jupyter:

jupyter notebook notebooks/TelecomX_LATAM.ipynb


	•	En Colab: subir TelecomX_LATAM.ipynb a tu cuenta de Colab.

	4.	Ejecutar celdas
	•	Corre celdas de carga y limpieza de datos (ETL).
	•	Corre celdas de EDA para reproducir gráficos e insights.
	5.	Explorar y modificar
	•	Ajusta parámetros y añade más visualizaciones según tus necesidades.

⸻

Autor: Jorge Ignacio Orsola Hernández

Fecha: Julio 2025
