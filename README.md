# Matching Networks

Este repositorio contiene el código fuente del proyecto final sobre la aplicación de **Machine Learning** (Perceptrón Multicapa) para resolver el problema del matrimonio estable de **Gale-Shapley** (Teoría de Juegos) con preferencias incompletas.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](ENLACE_A_TU_NOTEBOOK_EN_COLAB)

En el problema clásico de asignación, se asume que todos los participantes conocen sus preferencias de forma estricta y ordenada. En este trabajo, utilizamos datos reales del *Speed Dating Experiment* de la Universidad de Columbia para inferir estas preferencias mediante Inteligencia Artificial.

El pipeline consta de:
1. Limpieza de datos y prevención de *Data Leakage*.
2. Entrenamiento de dos Redes Neuronales independientes (para preferencias masculinas y femeninas).
3. Generación de listas de preferencias estrictas a partir de las probabilidades continuas.
4. Algoritmo de Gale-Shapley: Ejecución del emparejamiento estable óptimo.
5. Verificación computacional de la ausencia de pares de bloqueo.

Para ejecutar el código:
1. Haz clic en el botón **"Open in Colab"** de arriba.
2. En el menú superior de Colab, selecciona `Entorno de ejecución > Ejecutar todas`.
3. El código descargará automáticamente el dataset y ejecutará el entrenamiento y la simulación paso a paso.

## Dataset
Se ha utilizado el [Speed Dating Experiment](https://www.kaggle.com/annavictoria/speed-dating-experiment) (Kaggle). El archivo CSV necesario está incluido en este repositorio para facilitar la ejecución automática del script.
