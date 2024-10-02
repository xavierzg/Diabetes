# Diabetes
## Introducción
El Conjunto de Datos de Diabetes de las Mujeres Pima, originario del Instituto 
Nacional de Diabetes y Enfermedades Digestivas y Renales, contiene información de 
768 mujeres de una población cerca de Phoenix, Arizona, EE. UU. La variable objetivo 
evaluada fue la diabetes, de las cuales 258 dieron positivo y 500 negativo. Por lo 
tanto, hay una variable objetivo y los siguientes atributos : <br>
• Pregnancies (número de veces embarazada), <br>
• Oral glucose tolerance test  (concentración de glucosa en plasma a las dos 
horas después de 75 g de glucosa anhidra en mg/dl), <br>
• Blood pressure (Presión Arterial Diastólica en mmHg), <br>
• Skin thickness (grosor del pliegue cutáneo del tríceps en mm), <br>
• Insulin (insulina sérica a las 2 horas en mu U/ml), <br>
• BMI (Índice de Masa Corporal en kg/m²), <br>
• Age (años), <br>
• DiabetesPedigreeFunction (función que representa cuán probable es que 
contraigan la enfermedad extrapolando la historia de sus ancestros).
## Objetivos
Hacer un análisis del conjunto de datos y prepararlos para ser usados por diversos 
algoritmos. <br>
Seleccionar el algoritmo con mejor rendimiento sobre el conjunto.

## Este repositorio incluye los siguientes archivos:
El análisis de los datos y el proceso para limpiarlo (EDA.ipynb) <br>
Implementación de diversos algoritmos (Model.ipynb) <br>
Raw data (diabetes.csv) <br>
Datos limpios (datos_limpios.csv) <br>
Un reporte explicando lo que se hizo paso a paso y el por qué de la toma de decisiones (Reporte_diabetes.pdf)
## Este proyecto sigue los siguientes pasos :
1. Análisis sencillo de los datos. <br>
2. Limpieza de nans y outliers. <br>
3. Correlación e importancia de variables. <br>
4. Implementación de algoritmos. <br>
5. Uso y análisis de diferentes métricas <br>
6. Análisis de separación de los datos en entrenamiento y prueba.

## Conclusión
Esto es para 5 diferentes divisiones de los datos 

| Modelo            | Valid Accuracy  | Test Accuracy   | Valid F1        | Test F1         | Valid Recall     | Test Recall      | Valid Precision   | Test Precision    |
|-------------------|-----------------|-----------------|------------------|------------------|------------------|------------------|-------------------|-------------------|
| XGBoost           | 0.765 ± 0.007   | 0.756 ± 0.031   | 0.702 ± 0.010    | 0.692 ± 0.039    | 0.794 ± 0.019    | 0.796 ± 0.090    | 0.632 ± 0.007     | 0.616 ± 0.038     |
| Random Forest     | 0.773 ± 0.006   | 0.745 ± 0.017   | 0.647 ± 0.010    | 0.602 ± 0.061    | 0.601 ± 0.012    | 0.566 ± 0.105    | 0.707 ± 0.013     | 0.653 ± 0.020     |
| K Neighbors       | 0.772 ± 0.007   | 0.740 ± 0.016   | 0.638 ± 0.015    | 0.595 ± 0.041    | 0.581 ± 0.027    | 0.558 ± 0.092    | 0.716 ± 0.022     | 0.650 ± 0.047     |
| Gradient Boosting | 0.769 ± 0.010   | 0.748 ± 0.026   | 0.648 ± 0.015    | 0.614 ± 0.065    | 0.612 ± 0.020    | 0.589 ± 0.109    | 0.695 ± 0.017     | 0.654 ± 0.043     |

