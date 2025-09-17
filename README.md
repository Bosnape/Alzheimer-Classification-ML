# Clasificación de Enfermedad de Alzheimer - Pipeline de Machine Learning

## Descripción del Proyecto

Este proyecto implementa un pipeline completo de machine learning para la **clasificación binaria de la enfermedad de Alzheimer**. El objetivo es desarrollar y comparar múltiples modelos predictivos para determinar si un paciente tiene o no diagnóstico de Alzheimer basándose en mediciones clínicas, factores demográficos y de estilo de vida.

## Planteamiento del Problema

La detección temprana del Alzheimer es crucial para la planificación del tratamiento. Este proyecto aborda la clasificación binaria para determinar la presencia o ausencia de la enfermedad utilizando enfoques de machine learning y deep learning.

**Tipo de Problema**: Clasificación Binaria  
**Variable Objetivo**: Diagnóstico de Alzheimer (Sí/No)  
**Enfoque**: Aprendizaje Supervisado con comparación de modelos

## Información del Dataset

El dataset contiene información clínica y demográfica de pacientes:

- **Detalles demográficos**: Edad, genero, etnicidad y nivel de educacion.
- **Factores del estilo de vida**: Indice de masa corporal, si fuma o no, consumo de alcohol, actividad fisica, calidad de la dieta y calidad del sueño.
- **Historial medico**: Antecedentes familiares de alzheimer, enfermedad cardiovascular, diabetes, depresion, traumatismo en la cabeza e hipertension.
- **Medidas clinicas**: Presion arterial sistolica, presion arterial diastolica, colesterol total, colesterol LDL, colesterol HDL y colesterol trigliceridos.
- **Evaluaciones cognitivas y funcionales**: Evaluacion MMSE, evaluacion funcional, quejas de memoria, problemas de comportamiento y evaluacion ADL.
- **Sintomas**: Confusion, desorientación, cambios en la personalidad, dificultad para completar tareas y problemas de olvido.
- **Informacion diagnostica**: diagnostico de alzheimer.

**Fuente del Dataset**: [Alzheimer's Disease Dataset - Kaggle](https://www.kaggle.com/datasets/rabieelkharoua/alzheimers-disease-dataset)

## Enfoque Técnico

### Modelos Implementados:
1. **K-Nearest Neighbors (KNN)** - Aprendizaje basado en instancias
2. **Modelo de ensamble (Random Forest o Gradient Boosting)** - Método de ensamble con análisis de importancia de características
3. **Deep Neural Network (DNN)** - Arquitectura multicapa con regularización

### Componentes del Pipeline:
- **Análisis Exploratorio de Datos (EDA)** - Comprensión completa de los datos
- **Preprocesamiento de Datos** - Limpieza, codificación y normalización
- **Ingeniería de Características** - Selección y transformación
- **Entrenamiento y Validación de Modelos** - Ajuste de hiperparámetros
- **Evaluación de Rendimiento** - Comparación de métricas y análisis

## Características Principales

- Flujo completo de ciencia de datos desde EDA hasta despliegue de modelos
- Análisis comparativo de enfoques tradicionales de Machine Learning vs Deep Learning
- Análisis estadístico de importancia de características y correlaciones
- Pruebas con muestras artificiales para validación de modelos
- Visualizaciones e interpretaciones pertinentes

## Estructura del Proyecto

```
Alzheimer-Classification-ML/
├── data/                         # Archivo del dataset
├── docs/                         # Documentación y diagramas
├── alzheimer_ml_analysis.ipynb   # Notebook principal de análisis
├── README.md                     # Descripción general del proyecto
└── requirements.txt              # Dependencias de Python
```

## Más Información

Para obtener información detallada sobre la metodología, análisis y resultados del proyecto, consulta la [Wiki del proyecto](https://github.com/Bosnape/Alzheimer-Classification-ML/wiki).

## Citación del Dataset

```bibtex
@misc{rabie_el_kharoua_2024,
    title={Alzheimer's Disease Dataset},
    url={https://www.kaggle.com/dsv/8668279},
    DOI={10.34740/KAGGLE/DSV/8668279},
    publisher={Kaggle},
    author={Rabie El Kharoua},
    year={2024}
}
```