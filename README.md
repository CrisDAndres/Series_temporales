# Predicción de Series Temporales de Aguacates

## Descripción General

Este proyecto se centra en la predicción del precio de los aguacates utilizando técnicas avanzadas de predicción de series temporales. Para ello, se emplean dos enfoques principales: ARIMA y Prophet. ARIMA es un modelo estadístico ampliamente utilizado para el análisis de series temporales, que captura las dependencias autoregresivas e integradas en los datos. Por otro lado, Prophet, desarrollado por Facebook, es una poderosa herramienta que permite ajustar tendencias no lineales y estacionalidades con mayor flexibilidad.

El objetivo del proyecto es aprovechar los datos históricos de precios de aguacates para predecir precios futuros, identificar tendencias, y entender los patrones estacionales, de manera que sirva de utilidad para la toma de decisiones estratégicas.

## Estructura del proyecto 📂

El proyecto consiste en los siguientes archivos:

- ``data/``: Carpeta que contiene el conjunto de datos utilizado en este proyecto en formato .csv. El dataset consiste en precios históricos de aguacates en diferentes regiones de EEUU.
- ``avocado.ipynb``: Notebook de Jupyter con el código utilizado para realizar el análisis de la serie temporal, con explicaciones detalladas de cada paso.
- ``img/``: Carpeta que contiene imágenes del proyecto.

## Tecnologías utilizadas 🛠️

- Lenguaje de programación:

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
- Bibliotecas y Frameworks para Modelado:

![Prophet](https://img.shields.io/badge/Prophet-3776AB?style=for-the-badge&logo=python&logoColor=white) 
![ARIMA](https://img.shields.io/badge/ARIMA-007D3C?style=for-the-badge&logo=python&logoColor=white)  
![statsmodels](https://img.shields.io/badge/statsmodels-3776AB?style=for-the-badge&logo=python&logoColor=white)
- Manipulación y análisis de datos:

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
- Visualización de datos:

![Matplotlib](https://img.shields.io/badge/Matplotlib-007ACC?style=for-the-badge&logo=python&logoColor=white)  
![Seaborn](https://img.shields.io/badge/Seaborn-3776AB?style=for-the-badge&logo=python&logoColor=white)  
- Entornos de desarrollo:

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![VSCode](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

## Instrucciones de ejecución 💻
Para ejecutar este proyecto en tu máquina local, sigue los siguientes pasos:

1. Clona este repositorio en tu máquina local.
2. Descarga las carpetas ``data``,``models`` y ``notebook``, así como el script de Python ``plant_stress.py``.
3. Instala las dependencias necesarias ejecutando ``pip install -r requirements.txt``.
4. Ejecuta el archivo ``plant_stress.py`` y asegúrate de que has descargado las carpetas en el mismo entorno. A continuación, abre la terminal y ejecuta el siguiente comando: ``streamlit run plant_stress.py``. Esto abrirá el navegador web ``http://localhost:8501/`` que te llevará a la aplicación.
5. Carga una imagen desde tu ordenador y presiona el botón de **Clasificar imagen** para ver la clasificación de la enfermedad de la hoja. 

## Contacto 📧
Si tienes alguna pregunta o sugerencia sobre este proyecto, no dudes en ponerte en contacto conmigo. Puedes hacerlo a través de mis redes sociales.