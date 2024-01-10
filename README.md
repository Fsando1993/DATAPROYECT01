<h2 align="center"> Proyecto-ML-STEAM </h2>
![Uploading image.png…]()



TECNOLOGIAS:


![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)
![Microsoft](https://img.shields.io/badge/Microsoft-0078D4?style=for-the-badge&logo=microsoft&logoColor=white)
![Render](https://img.shields.io/badge/Render-%46E3B7.svg?style=for-the-badge&logo=render&logoColor=white)

Introducción

Bienvenidos a mi proyecto de Machine Learning de Steam. Mi nombre es Ana Florencia Sandoval, estoy cursando la carrera de Data Science en la cohorte-18 en Soy Henry.

El desafío planteado para este proyecto consiste en desarrollar un proceso de MLOps que incluya etapas de Ingeniería de Datos con Extraction, Transform and Load (ETL), pasando al Machine Learning, con Exploratory Data Analysis (EDA), junto con la exploración y entrenamiento de modelos, finalizando con el deployment tanto del modelo como endpoints.

Objetivos

Queremos desarrollar y desplegar un sistema de recomendacion de juegos, teniendo endopints que se consumen online y pueden responder las funciones que nos pidieron para desarrollar Esto lo vamos a hacer aprovechando los conjuntos de datos y nos enfocaremos en lograr los siguientes hitos específicos:

Hito 1: Extracción y transformación de los datos de Steam.
Hito 2: Exploración y análisis de los datos.
Hito 3: Entrenamiento de modelos de recomendación.
Hito 4: Evaluación de los modelos de recomendación.
Hito 5: Despliegue de los modelos de recomendación.
MLOps: Gestión Eficiente

Estableceremos una infraestructura de MLOps para navegar sin problemas por todas las etapas de este emocionante proyecto. Desde la transformación de datos hasta el despliegue, estamos comprometidos con una operación eficiente y sin contratiempos.


## Ámbito de Proyecto

- Preprocesamiento de datos y analisis exploratorio de las base:
  
  [1-ETL-EDA](1-ETL-EDA.ipynb)
  
  [2-ETL-Consultas](2-ETL-Consultas.ipynb)

- Desarrolo del modelo de aprendizaje:

  [3-Modelo Machine Learning](3-Modelo-ML-item-item.ipynb)


- Desarrollo de funciones y API's:

  [Prueba de las funciones](Prueba_Funciones.ipynb)
  
  [Funciones API](funciones.py)
  
  [Main Funciones](main.py)
  
  [Requerimientos](requirements.txt)





  ## Pasos realizados para el proyecto

- ETL (Extract, Transform, Load) y EDA (Exploratory Data Analysis)

En esta fase del proyecto, se llevaron a cabo las siguientes actividades:

Extracción de Datos (Extract): Se Extrageron los datos que nos proporcionaron en Formato JSON. Son 3 bases con informacion de los juegos de Steam, Reviews y datos de usuarios.

Transformación de Datos (Transform): Los datos fueron procesados y transformados para asegurar la coherencia y la integridad. Esto incluyó la limpieza de datos, la estandarización de formatos, tipos de datos y la manipulación de variables para prepararlos para el análisis.

Carga de Datos (Load): Los datos transformados fueron cargados en el entorno de trabajo,en formato .csv y cargados en github, para facilitar su acceso y análisis posterior.

Análisis Exploratorio de Datos (EDA): Se llevó a cabo un análisis exploratorio para comprender mejor la naturaleza de los datos. Esto incluyó la visualización de patrones, la identificación de tendencias y la detección de posibles relaciones entre variables clave.

- Machine Learning:

En la fase de Machine Learning, se realizaron los siguientes pasos:

Selección de Modelos: Se selecciono el modelo de machine learning de relacion item-item, y se analizaron las bases propuestas para generear una solucion específica.

Entrenamiento del Modelo: Los modelos seleccionados fueron entrenados utilizando los datos previamente procesados durante la fase ETL. Se llevaron a cabo ajustes y optimizaciones para mejorar el rendimiento del modelo.

Validación del Modelo: Se realizaron pruebas y validaciones cruzadas para evaluar la precisión y la generalización del modelo en conjuntos de datos independientes.

Optimización del Modelo: Se realizaron ajustes adicionales para optimizar el modelo.

- Deployment y API:

Montaje de la API (Local): Se implementó  un entorno virtual para permitir la interacción con el modelo de machine learning y las consultas antes pedidas.

Despliegue en Render (Deploy-Render): Se procedió al despliegue de la API en un entorno de producción utilizando las plataformas Render y github en la nube. Esto permitió que la funcionalidad estuviera disponible de manera accesible para usuarios finales.

Monitoreo y Mantenimiento: Se probaron tanto el modelo como los endpoints para chequear su rendimiento y velocidad de respuesta  en tiempo real de la API desplegada. 

## Video

Dejo el video proporcionando una explicacion basica del proyecto, y el funcionamiento de los endpoints
