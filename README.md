# Proyecto 2 - Minería de Datos

## Link del Repositorio
* https://github.com/paulabaal12/PROY2-DM

## Integrantes del equipo
- [Mónica Salvatierra - 22249](https://github.com/alee2602)
- [Paula Barillas - 22764](https://github.com/paulabaal12)
- [Derek Arreaga - 22537](https://github.com/FabianKel) 
- [Juan Pablo Solís - 22102](https://github.com/JPS4321)

## Introducción
El presente proyecto consiste en el análisis de datos sobre el conjunto de datos "[House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)", disponible en Kaggle. A través de técnicas avanzadas de minería de datos, específicamente análisis exploratorio y modelos de regresión, se busca estimar el precio de una casa basado en diversas características.

## Objetivo del Proyecto
El objetivo es desarrollar modelos predictivos que permitan estimar de manera precisa el valor de una vivienda, utilizando un conjunto de datos que recopila información detallada sobre propiedades. Para ello, se emplearán técnicas de regresión y clasificación para determinar el mejor modelo de predicción, considerando diferentes algoritmos y parámetros.

## Contenido:
- **Parte 1: Análisis Exploratorio y Modelo de Regresión Lineal**
    - [proyecto.ipynb](proyecto.ipynb)
        - **Análisis Exploratorio de Datos (EDA)**: Inspección y visualización de los datos para identificar patrones y relaciones entre las variables.
        - **Preprocesamiento de Datos**: Limpieza y transformación de los datos para adecuarlos a los modelos.
        - **Construcción y Evaluación del Modelo de Regresión Lineal**: Desarrollo del modelo de regresión lineal para predecir el precio de las viviendas, seguido de su evaluación utilizando métricas de desempeño.
- **Parte 2: Árbol de Regresión y Clasificación**
    - [proyectoE2.ipynb](proyectoE2.ipynb)
        - **Construcción y Evaluación de un Árbol de Regresión**: Análisis del desempeño del modelo de árbol de regresión variando la profundidad del árbol para mejorar la predicción.
        - **Creación de una Nueva Variable Objetivo**: Se crea una variable categórica ```PriceCategory``` para clasificar las viviendas en 3 categorías: Económicas, Intermedias, y Caras, según el rango de precios.
        - **Construcción y Evaluación de un Árbol Categórico**: Desarrollo de un modelo de árbol de decisión para predecir la categoría de precio de la vivienda utilizando la variable ```PriceCategory```.
        - **Métricas de Desempeño del Árbol Categórico**: Evaluación del desempeño del modelo de árbol categórico utilizando métricas como precisión, recall y F1-score.

## Instrucciones para ejecutar el proyecto
Para ejecutar este proyecto, sigue los pasos detallados a continuación:
1. **Instalar las dependencias**: Asegúrate de tener ```pip``` instalado en tu entorno.  
    Luego, ejecuta el siguiente comando para instalar todas las dependencias necesarias:

    ```bash
    pip install -r requirements.txt
    ```
2. **Ejecutar el Proyecto**:

* El proyecto está dividido en Parte 1 y Parte 2, cada una contenida en un archivo .```ipynb```:

    * **Parte 1**: [proyecto.ipynb](proyecto.ipynb)

        Esta sección realiza el análisis exploratorio de los datos, el preprocesamiento y construye el modelo de regresión lineal.

    * **Parte 2**: [proyectoE2.ipynb](proyectoE2.ipynb)
    
        Esta parte construye y evalúa el modelo de árbol de regresión y el modelo de clasificación con una nueva variable PriceCategory.

    * **Importante**:

        Debes ejecutar primero la **Parte 1** ([proyecto.ipynb](proyecto.ipynb)) para realizar el análisis exploratorio y el preprocesamiento de los datos. Los resultados de esta etapa se utilizan como entrada para la **Parte 2** ([proyectoE2.ipynb](proyectoE2.ipynb)).
        
        Si se ejecuta la **Parte 2** sin haber ejecutado la **Parte 1**, es probable que cause errores relacionados con la falta de datos procesados correctamente.