# Predicción de Disponibilidad de Bicicletas - Proyecto Capstone

## Descripción General

Este repositorio contiene el código y la documentación para el proyecto **"Predicción Bicing Docks en Barcelona"**, parte del Proyecto Capstone. El objetivo de este proyecto es predecir el porcentaje de docks libres en las estaciones de Bicing utilizando datos históricos, así como explorar posibles nuevas ubicaciones para estaciones y entender cómo diferentes eventos afectan la disponibilidad de bicicletas.

## Tabla de Contenidos
- [Descripción General](#descripción-general)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Conjunto de Datos](#conjunto-de-datos)
- [Uso](#uso)
- [Modelado](#modelado)
- [Evaluación](#evaluación)
- [Resultados](#resultados)




## Conjunto de datos

El conjunto de datos incluye información histórica de las estaciones de Bicing desde 2020 hasta 2023 para entrenamiento y validación, y datos de 2024 para pruebas. También se incluye información adicional, como el clima y eventos del calendario, para mejorar las predicciones.

- **Datos de Entrenamiento/Validación**: 2021-2023
- **Datos de Prueba**: 2024
- **Información de Estaciones de Bicing**: Incluye capacidad de la estación, coordenadas y otros detalles relevantes.

## Uso
Preprocesamiento de Datos: Utilice los scripts en src/data_preprocessing.py para limpiar y preparar los datos.
Entrenamiento del Modelo: Utilice los scripts en src/modeling.py para entrenar su modelo.
Evaluación del Modelo: Utilice los scripts en src/evaluation.py para evaluar el rendimiento de su modelo.

## Modelado
El enfoque principal del modelado es predecir el porcentaje de anclajes libres en cada estación de Bicing utilizando datos históricos y características adicionales como el clima y eventos del calendario.

## Evaluación
La evaluación del modelo se realiza mediante una competencia en Kaggle, donde se comparan las predicciones con datos reales de 2024.

## Resultados
Los resultados obtenidos se presentarán en un blog o página de GitHub, mostrando visualizaciones
