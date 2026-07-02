# NTSB Aviation Safety Analysis

## Descripción

Proyecto desarrollado para el curso de Programación y Métodos Numéricos.

El objetivo es realizar un análisis exploratorio de los accidentes e incidentes
aeronáuticos registrados por la National Transportation Safety Board (NTSB),
empleando técnicas de análisis de datos y visualización en Python.

---

# Objetivo General

Desarrollar una metodología computacional para el análisis de accidentes e incidentes aeronáuticos mediante programación científica, análisis exploratorio de datos, procesamiento de lenguaje natural, métodos numéricos y modelos de aprendizaje automático.

---

## Objetivos

- Implementar una estructura organizada y reproducible para el desarrollo del proyecto utilizando Python y GitHub.
- Realizar la carga, auditoría, validación y limpieza del conjunto de datos de la National Transportation Safety Board (NTSB).
- Desarrollar un Análisis Exploratorio de Datos (EDA) que permita comprender la calidad, estructura y comportamiento estadístico del conjunto de datos.
- Aplicar técnicas de Procesamiento de Lenguaje Natural (NLP) sobre la variable **ProbableCause** para extraer información relevante de las descripciones textuales de los accidentes.
- Implementar métodos numéricos para apoyar el procesamiento y análisis computacional de la información.

---
# Dataset

**Fuente**

National Transportation Safety Board (NTSB)

https://www.ntsb.gov/

**Archivo utilizado**

```
data/raw/NTSB Accident data.csv
```

El conjunto de datos contiene información histórica sobre accidentes e incidentes aeronáuticos, incluyendo variables relacionadas con:

- Fecha del evento
- Ubicación geográfica
- Fabricante y modelo
- Categoría de aeronave
- Tipo de operación
- Condiciones meteorológicas
- Nivel de lesiones
- Daños de la aeronave
- Descripción de la causa probable del accidente

---

## Estructura del proyecto

```
Proyecto-PMN
│
├── data
│   └── raw
│       └── NTSB Accident data.csv
│
├── outputs
│   └── Mapa_Accidentes.html
│
├── figures
│
├── models
│
├── PMN_EDA_Proyecto.ipynb
│
├── README.md
│
└── .gitignore
```

---

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Plotly
- Folium
- Scikit-Learn
- Google Colab
- Git
- GitHub

---

# Resultados Esperados

Al finalizar el proyecto se dispondrá de:

- Un flujo de trabajo completamente reproducible para el análisis de datos aeronáuticos.
- Un análisis exploratorio exhaustivo del conjunto de datos de la NTSB.
- Un sistema de procesamiento de lenguaje natural aplicado a las causas probables de accidentes.
- Un conjunto de datos preparado para tareas de aprendizaje automático.
- Un modelo basado en redes neuronales para apoyar la clasificación de eventos aeronáuticos.
- Un repositorio organizado, documentado y versionado mediante Git y GitHub.

---

## Autor

José Luis Martínez Díaz

Universidad Nacional de Colombia

Programa de Física
