Predicción de Cancelación de Clientes (Churn Prediction) 📉
Este repositorio contiene un proyecto de análisis de datos y machine learning enfocado en la predicción de la cancelación de clientes (churn) para una empresa de telecomunicaciones. El objetivo principal es identificar los factores clave que influyen en la decisión de un cliente de cancelar su servicio y desarrollar modelos predictivos para anticipar este comportamiento. 🎯

Contenido del Repositorio 🗄️
notebook.ipynb: El notebook principal de Jupyter que contiene todo el código y análisis, incluyendo:
Carga y preparación de los datos. 🛠️
Exploración inicial y visualización de datos. 📊
Preprocesamiento de datos (manejo de valores nulos, codificación de variables categóricas, balanceo de clases con SMOTE, escalado). ✨
Modelado predictivo utilizando Regresión Logística y Random Forest. 🤖
Evaluación y comparación de modelos. 🕵️📊
Análisis de la importancia de las características. 🔑🧐
Interpretación de resultados y propuestas de estrategias de retención. 📄💡
datos__final.csv: El conjunto de datos utilizado para el análisis y la construcción de modelos. 💾
Metodología 📈
El proyecto sigue un flujo de trabajo típico de ciencia de datos:

Preparación de Datos: Limpieza, transformación y preparación del conjunto de datos para el modelado. Esto incluyó el manejo de columnas irrelevantes, la codificación de variables categóricas mediante one-hot encoding, la imputación de valores nulos y el balanceo del conjunto de entrenamiento utilizando SMOTE para abordar el desbalance de clases. ✨
Análisis Exploratorio y de Correlación: Visualización de la matriz de correlación y diagramas de caja para entender las relaciones entre las variables y la variable objetivo (cancelación). 📊
Modelado Predictivo: Implementación y entrenamiento de dos modelos de clasificación: Regresión Logística y Random Forest. 🤖
Evaluación de Modelos: Comparación del rendimiento de los modelos utilizando métricas como Accuracy, Precision, Recall y F1-score, así como el análisis de las matrices de confusión. 🕵️📊
Interpretación y Conclusiones: Análisis de la importancia de las características para identificar los principales impulsores de la cancelación y desarrollo de estrategias de retención basadas en los hallazgos. 📄💡
Resultados Clave 👇
El modelo de Random Forest demostró ser el más efectivo para predecir la cancelación, con una mayor precisión general y una mejor capacidad para identificar correctamente a los clientes que cancelarán. ✅🏆
Los factores más influyentes en la cancelación identificados por los modelos incluyen la duración del contrato (Meses_Conectado) ⏳, los cargos totales (Cargos_Totales) 💰, el método de pago (Método_Pago_Electronic check) 💳⚡️, el tipo de contrato (Tipo_Contrato_Month-to-month) 🗓️, y el servicio de internet (Servicio_Internet_Fiber optic) 🌐💡.
Estrategias de Retención Propuestas 🛡️🎯
Basado en el análisis, se proponen estrategias dirigidas a:

Fomentar contratos a largo plazo. 🤝🔒
Mejorar la experiencia de pago, especialmente para los usuarios de cheque electrónico. 💳✨
Optimizar la oferta y fiabilidad del servicio de fibra óptica. 🌐🔧
Implementar programas de lealtad y comunicación proactiva. ❤️🏆
Cómo Usar ▶️
Para replicar este análisis, clona el repositorio y ejecuta el notebook notebook.ipynb en un entorno con las bibliotecas de Python necesarias (pandas, sklearn, imblearn, seaborn, matplotlib, plotly). Asegúrate de que el archivo datos__final.csv esté en la misma ubicación que el notebook. 🐍

