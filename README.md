# Proyecto Chikungunya - Análisis y Modelo Binario

Este repositorio contiene el trabajo del módulo 10 enfocado en el análisis exploratorio de datos (EDA) y el desarrollo de un modelo de clasificación binaria para el dataset de Chikungunya.

## Introducción

El proyecto estudia datos de pacientes con posibles infecciones por Chikungunya. Se realizó un análisis exploratorio detallado y se evaluaron alternativas de modelos, incluyendo una versión multiclase con accuracy ~0.64, antes de elegir el modelo binario final.

Nos basamos en los archivos base del conjunto de datos y notebook de referencia disponible en:

https://data.mendeley.com/datasets/bv26kznkjs/1

## Estructura de archivos

- `Proyecto1_CHIKUNGUNYA_EDA.ipynb` - Notebook con el análisis exploratorio de datos (EDA), limpieza, visualizaciones y preparación de variables.
- `Proyecto1_Clasificacion_Binario_CHIKUNGUNYA.ipynb` - Notebook con la construcción, entrenamiento y evaluación de un modelo de clasificación binaria para predecir resultados relacionados con Chikungunya.
- `Proyecto1_Multiclase_CHIKUNGUNYA.ipynb` - Notebook de alternativa exploratoria multiclase (accuracy ~0.64) descartada en favor del modelo binario final.
- `data_set_unbalanced.csv` - Dataset resultante creado a partir de dos bases originales, con clase desequilibrada para trabajar la clasificación.
- `data/` - Carpeta con archivos de datos usados en el proceso de limpieza y entrenamiento.

## Objetivo

El resultado final trabajado es un **modelo binario**.

## Cómo usar

1. Abrir los notebooks con Jupyter Notebook / JupyterLab.
2. Ejecutar todas las celdas en orden.
3. Revisar visualizaciones y métricas de evaluación en `Proyecto1_Clasificacion_Binario_CHIKUNGUNYA.ipynb`.

## Integrantes

- Ericka Cori
- Paolo Ramos
- Gaston Nina

## Carpeta data

La carpeta `data/` contiene los archivos de datos base y auxiliares utilizados en el proyecto:

- `data_set_unbalanced.csv` - Dataset principal creado combinando y procesando dos bases originales.
- Otros archivos de datos (si existen) para ejercicios de limpieza, features y análisis.

## Notas

- Asegúrate de tener instaladas las librerías necesarias (pandas, numpy, scikit-learn, matplotlib, seaborn, etc.) para ejecutar los notebooks.
- Si necesitas reproducir el entorno, crea un `venv` y instala dependencias.

