# Predicción de Disponibilidad de Bicicletas - Proyecto Capstone

## Descripción General

Este repositorio contiene el código y la documentación para el proyecto **"Predicción Bicing Docks en Barcelona"**, parte del Proyecto Capstone. El objetivo de este proyecto es predecir el porcentaje de docks libres en las estaciones de Bicing utilizando datos históricos, así como explorar posibles nuevas ubicaciones para estaciones y entender cómo diferentes eventos afectan la disponibilidad de bicicletas.

## Tabla de Contenidos
- [Descripción General](#descripción-general)
- [Estructura del Proyecto](#estructura-del-proyecto)
- [Conjunto de Datos](#conjunto-de-datos)
- [Instalación](#instalación)
- [Uso](#uso)
- [Modelado](#modelado)
- [Evaluación](#evaluación)
- [Resultados](#resultados)
- [Contribuidores](#contribuidores)
- [Licencia](#licencia)

## Estructura del Proyecto

```plaintext
├── data
│   ├── raw                   # Datos en bruto
│   ├── processed             # Datos procesados
├── notebooks                 # Jupyter notebooks
├── src
│   ├── data_preprocessing.py # Scripts de preprocesamiento de datos
│   ├── modeling.py           # Scripts de modelado
│   ├── evaluation.py         # Scripts de evaluación
├── README.md
└── requirements.txt          # Dependencias necesarias
