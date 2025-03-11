Portafolio de Ciencia de Datos

Este repositorio contiene varios proyectos demostrativos que aplican técnicas de análisis de datos y Machine Learning en distintos conjuntos de datos.
Los proyectos incluyen:

Predicción de Precios de Autos: Basado en el Car Price Dataset.

Clasificación de Tumores Cerebrales: Utilizando el Brain Tumor Dataset.

1. Análisis y Modelado Predictivo de Precios de Autos

Descripción

Este proyecto analiza un conjunto de datos con información sobre 10,000 vehículos y sus principales características que influyen en su precio de mercado.

Contenido del Proyecto

Análisis Exploratorio de Datos (EDA)

Archivo: Analisis_Exploratorio_Car_Price_dataset.ipynb

Exploración detallada de las variables del dataset.

Análisis de la distribución de precios de los autos.

Relación entre marca, año de fabricación, tipo de combustible y precio.

Visualizaciones para una mejor interpretación de los datos.

Modelado Predictivo de Precios de Autos

Archivo: Modelado_Predictivo_de_Precios_de_Autos.ipynb

Aplicación de técnicas de Machine Learning para predecir precios.

Modelos de regresión y comparación de desempeño.

Evaluación de métricas de error para medir la precisión.

Descripción del Dataset

El dataset incluye la siguiente información de cada vehículo:

Brand: Marca del auto (Ejemplo: Toyota, BMW, Ford).

Model: Modelo del auto (Ejemplo: Corolla, Focus, X5).

Year: Año de fabricación (Ejemplo: 2005, 2018, 2023).

Engine_Size: Tamaño del motor en litros.

Fuel_Type: Tipo de combustible (Petrol, Diesel, Hybrid, Electric).

Transmission: Tipo de transmisión (Manual, Automática, Semi-Automática).

Mileage: Kilometraje del auto en kilómetros.

Doors: Número de puertas.

Owner_Count: Número de dueños previos.

Price: Precio estimado de venta del auto.

Fuente del Dataset

Car Price Dataset

2. Clasificación de Tumores Cerebrales

Descripción

Este proyecto utiliza un modelo de clasificación en Python con la biblioteca scikit-learn para predecir el tipo y la severidad de los tumores cerebrales.
El objetivo es ayudar a diagnosticar tumores cerebrales basados en diversas características de los pacientes y sus tumores.

Contenido del Proyecto

Archivo: Brain_Tumor_Clasificacion.ipynb

Construcción de un modelo de Machine Learning para clasificación de tumores.

Exploración y visualización de datos.

Evaluación del desempeño del modelo.

Descripción del Dataset

El dataset contiene 20 columnas y 20,000 registros con información sobre pacientes y sus tumores:

Patient_ID: Identificador del paciente.

Age: Edad del paciente.

Gender: Género del paciente.

Tumor_Type: Tipo de tumor (Benigno/Maligno).

Tumor_Size: Tamaño del tumor en cm.

Location: Parte del cerebro donde está localizado el tumor.

Histology: Tipo histológico del tumor.

Stage: Etapa del tumor (I-IV).

Symptom_1, Symptom_2, Symptom_3: Síntomas observados.

Radiation_Treatment, Surgery_Performed, Chemotherapy: Tratamientos recibidos.

Survival_Rate: Tasa de supervivencia.

Tumor_Growth_Rate: Tasa de crecimiento.

Family_History: Antecedentes familiares.

MRI_Result: Resultado de resonancia magnética.

Follow_Up_Required: Necesidad de seguimiento.

Treatment_Response: Respuesta al tratamiento.

Fuente del Dataset

Brain Tumor Dataset

Requisitos

Para ejecutar los notebooks, instala las siguientes librerías de Python:

pip install pandas numpy matplotlib seaborn scikit-learn

Uso

Clona este repositorio:

git clone https://github.com/HectorVejarCasillas/Portafolio-Ciencia-Datos

Abre los notebooks en Jupyter Notebook o Google Colab.

Ejecuta las celdas y explora los análisis y modelos.

Autor

Héctor Vejar Casillas

Este repositorio ha sido desarrollado como parte de mi portafolio para demostrar habilidades en análisis de datos y Machine Learning.

Si te interesa el proyecto, no dudes en darle una estrella ⭐ y contribuir con mejoras.

