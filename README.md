# Portafolio-Ciencia-Datos
Car Price Dataset - Análisis y Modelado Predictivo

Este repositorio contiene tres proyectos demostrativos basados en el Car Price Dataset y Brain tumor dataset, un conjunto de datos con información sobre 10,000 vehículos y sus principales características que influyen en su precio de mercado y brain tumor dataset que contiene datos simulados para diagnostico de tumores malignos y benignos.

# Contenido del Repositorio

1. Análisis Exploratorio de Datos (EDA)

Archivo: Analisis_Exploratorio_Car_Price_dataset.ipynb

Realiza un análisis detallado de las variables del dataset.

Explora la distribución de los precios de los autos.

Examina la relación entre factores como la marca, el año de fabricación, el tipo de combustible y el precio.

Incluye visualizaciones para facilitar la interpretación de los datos.

2. Modelado Predictivo de Precios de Autos

Archivo: Modelado_Predictivo_de_Precios_de_Autos.ipynb

Aplica técnicas de Machine Learning para predecir el precio de un auto en base a sus características.

Utiliza modelos de regresión y compara su desempeño.

Evalúa métricas de error para determinar la precisión de las predicciones.

Descripción del Dataset

El dataset incluye la siguiente información sobre cada vehículo:

Brand: Marca del auto (Ejemplo: Toyota, BMW, Ford).

Model: Modelo del auto (Ejemplo: Corolla, Focus, X5).

Year: Año de fabricación (Ejemplo: 2005, 2018, 2023).

Engine_Size: Tamaño del motor en litros (Ejemplo: 1.6, 2.0, 3.5).

Fuel_Type: Tipo de combustible (Petrol, Diesel, Hybrid, Electric).

Transmission: Tipo de transmisión (Manual, Automática, Semi-Automática).

Mileage: Kilometraje del auto en kilómetros (Ejemplo: 15,000, 75,000, 230,000).

Doors: Número de puertas (Ejemplo: 2, 3, 4, 5).

Owner_Count: Número de dueños previos (Ejemplo: 1, 2, 3, 4).

Price: Precio estimado de venta del auto (Ejemplo: 5,000, 15,000, 30,000).

Requisitos

Para ejecutar los notebooks, necesitas instalar las siguientes librerías de Python:

pip install pandas numpy matplotlib seaborn scikit-learn

Uso

Clona este repositorio:

git clone https://github.com/HectorVejarCasillas/Portafolio-Ciencia-Datos

Abre los notebooks en Jupyter Notebook o Google Colab.

Ejecuta las celdas y explora los análisis y modelos.

# Autor Hector vejar casillas

Este repositorio ha sido desarrollado como parte de mi portafolio para demostrar habilidades en análisis de datos y Machine Learning.

Si te interesa el proyecto, no dudes en darle una estrella ⭐ y contribuir con mejoras.



# Fuentes:
Dataset:  https://www.kaggle.com/datasets/asinow/car-price-dataset

# Brain Tumor Classification Project
Este proyecto utiliza un modelo de clasificación en Python con la biblioteca scikit-learn para predecir el tipo y la severidad de los tumores cerebrales a partir de un conjunto de datos proporcionado por Kaggle. El objetivo es ayudar a diagnosticar tumores cerebrales basados en diversas características de los pacientes y sus tumores.

# Dataset
El dataset utilizado en este proyecto es el Brain Tumor Dataset que contiene datos simulados sobre diagnóstico, tratamiento y detalles de pacientes con tumores cerebrales. El conjunto de datos contiene 20 columnas y 20,000 filas, proporcionando información sobre la demografía del paciente, las características del tumor, los síntomas y los tratamientos administrados, entre otros.

# Columnas del Dataset:
Patient_ID: Identificador único del paciente.
Age: Edad del paciente (en años).
Gender: Género del paciente (Masculino/Femenino).
Tumor_Type: Tipo de tumor (Benigno/Maligno).
Tumor_Size: Tamaño del tumor en centímetros.
Location: Parte del cerebro donde está localizado el tumor (e.g., Frontal, Temporal).
Histology: Tipo histológico del tumor (e.g., Astrocitoma, Glioblastoma).
Stage: Etapa del tumor (I, II, III, IV).
Symptom_1: Primer síntoma observado (e.g., Dolor de cabeza, Convulsiones).
Symptom_2: Segundo síntoma observado.
Symptom_3: Tercer síntoma observado.
Radiation_Treatment: Si el paciente recibió tratamiento de radiación (Sí/No).
Surgery_Performed: Si se realizó cirugía (Sí/No).
Chemotherapy: Si el paciente recibió quimioterapia (Sí/No).
Survival_Rate: Tasa estimada de supervivencia del paciente (en porcentaje).
Tumor_Growth_Rate: Tasa de crecimiento del tumor (cm por mes).
Family_History: Si el paciente tiene antecedentes familiares de tumores cerebrales (Sí/No).
MRI_Result: Resultado de la resonancia magnética (Positivo/Negativo).
Follow_Up_Required: Si es necesario un seguimiento (Sí/No).
Treatment_Response: Respuesta al tratamiento (Mejorado/Agravado/Estable).
Objetivo del Proyecto
El objetivo de este proyecto es construir un modelo de clasificación para predecir el tipo de tumor (Benigno o Maligno) basándose en las características del paciente y del tumor, utilizando técnicas de aprendizaje automático.

# Dependencias
Este proyecto fue desarrollado utilizando las siguientes bibliotecas de Python:

pandas - Para la manipulación y análisis de datos.
numpy - Para operaciones matemáticas.
scikit-learn - Para la construcción de los modelos de clasificación y evaluación.
matplotlib y seaborn - Para la visualización de los resultados.
# Fuente:
https://www.kaggle.com/datasets/miadul/brain-tumor-dataset
