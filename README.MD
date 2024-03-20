# Análisis de Modelamiento para Predicción de Sobrepeso

## Resumen
Este proyecto se centra en el análisis y comparación de varios modelos de aprendizaje automático para predecir la probabilidad de sobrepeso en una población. Se han evaluado tres tipos de modelos: Regresión Logística Multinomial, Random Forest y Red Neuronal, con el objetivo de determinar el más eficaz para esta tarea.

## Métodos de Modelamiento
Se han utilizado los siguientes métodos para modelar y evaluar los modelos:

1. **Regresión Logística Multinomial**
2. **Random Forest**
3. **Red Neuronal**

## Resultados
Los modelos han arrojado los siguientes resultados en términos de precisión (Accuracy):

- **Regresión Logística Multinomial:** 60%
- **Random Forest:** 82.26%
- **Red Neuronal:** 89%

## Análisis de Resultados
- Para la predicción única del sobrepeso, el modelo Random Forest ofrece la mayor precisión.
- Sin embargo, al considerar todos los niveles de sobrepeso, la red neuronal es considerablemente más precisa.
- Se destaca la importancia de variables como Smoke, SCC, Gender, Family history with overweight y FAVC en la predicción del sobrepeso.

## Detalles de Implementación
- Se ha agregado dropout a las capas de la red neuronal para evitar el sobreajuste.
- El número de neuronas en la primera capa densa se aumentó a 128 para mejorar la capacidad de aprendizaje de la red neuronal.

## Archivos
- `Datos/`: Carpeta que contiene los datos utilizados para el análisis.
- `1_Exploracion_datos.ipynb`: Cuaderno Jupyter con el código para el análisis exploratorio de los datos.
- `2_aprendizaje_supervisado.ipynb`: Cuaderno Jupyter con el código para el modelamiento y análisis de resultados.
- `README.txt`: Este archivo, que proporciona una descripción general del proyecto.
- `requirement.txt`: Este archivo, que proporciona una descripción de las librerias y versiones necesarias para ejecutar los notebooks.

## Autores
- Eduardo Useche
- Santiago Rodríguez Caicedo
