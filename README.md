<h1 align="center">
Estrategia de retención de clientes con ML (Pronósticos y predicciones)
</h1>

## Objetivo 

Desarrollar un modelo de Machine Learning capaz de predecir la probabilidad de pérdida de un cliente de la cadena de gimnasios Model Fitness para el próximo mes, y utilizar el análisis de datos para generar una estrategia de retención dirigida y rentable.

Este proyecto demuestra mi capacidad para aplicar técnicas analíticas avanzadas para **resolver problemas de negocio complejos**, identificar patrones ocultos en grandes conjuntos de datos (Big Data) y generar **conclusiones accionables**.

## Problema 🤔

Alta tasa de churn (pérdida de clientes).

## Solución 💡 

Implementación de modelos de clasificación y clustering para segmentar a los usuarios y entender las variables de entrada que conducen a la "falla del sistema" (la cancelación).

## Pipeline de análisis y modelado de datos 📑

| Etapa del Proyecto | Descripción Técnica | Habilidades |
| --- | --- | --- |
| **Análisis Exploratorio (EDA)** | Inspección de datos, cálculo de medias por grupo (Churn=0 vs Churn=1) y visualización de distribuciones para identificar la separación entre clientes activos y perdidos. | Análisis, Visualización de Datos. |
| **Modelado Predictivo** | Entrenamiento de modelos de **Clasificación Binaria** (LogisticRegression y RandomForestClassifier) para determinar qué clientes tienen alto riesgo de cancelación. | Machine Learning, Evaluación de Modelos. |
| **Clustering** | Uso de **K-Means** (Clustering no supervisado) para segmentar a los clientes en grupos homogéneos. | Segmentación, Interpretación de Datos. |
| **Generación de Recomendaciones** | Traducción de los hallazgos del modelo y los clústeres en **estrategias de retención** claras y dirigidas. | Pensamiento Crítico, Comunicación Técnica. |
<br>

## 🧰⚙️🛠️
<br>
<p align="left"> 
  &emsp;
   <a href="https://www.python.org" target="_blank">
    <img alt="Python" src="https://img.shields.io/badge/Python%20-%2314354C.svg?style=plastic&logo=python&logoColor=white">
  </a>
  &emsp;
  <a href="#"><img alt="Pandas" src="https://img.shields.io/badge/Pandas-%2334A853.svg?"></a>
  &emsp;
  <a href="#"><img alt="NumPy" src="https://img.shields.io/badge/Numpy-0078d7.svg?"></a>
    &emsp;
  <a href="#"><img alt="Scikit learn" src="https://img.shields.io/badge/Scikit learn-%234479A1.svg?"></a>
  &emsp;
  <a href="#"><img alt="Seaborn" src="https://img.shields.io/badge/Seaborn-%23F7DF1E.svg?"></a>
  &emsp;
  <a href="#"><img alt="Matplotlib" src="https://img.shields.io/badge/Matplotlib-%23FFA116.svg?"></a>
</p>
<br>

## Resultados y Conclusiones Principales 📊✔️

El análisis identificó los factores que más influyen en la retención y la pérdida: 📉📈

1. **Factores Clave de Retención/Pérdida:** Los atributos que más impactan la cancelación son: **Antigüedad** (Lifetime), **Periodo del Contrato** (Contract_period), **Frecuencia de Asistencia** (Avg_class_frequency_total), **Edad** (Age) y **Cercanía a la Ubicación** (Near_Location).
2. **Identificación de Clústeres de Riesgo:** La segmentación por K-Means reveló grupos de alto riesgo (grupos 4 y 2) caracterizados por:
   - Ser clientes muy **nuevos (bajo Lifetime)**.
   - Tener contratos de solo **1 mes**.
   - Una baja frecuencia de asistencia al gimnasio.
3. **Recomendaciones de Retención:** Se sugieren estrategias de marketing específicas (descuentos y promociones) dirigidas a estos grupos vulnerables para animarlos a extender su suscripción y aumentar la frecuencia de asistencia.

## Instrucciones de Uso 🗒️👩‍💻

1.	**Clonar el Repositorio**
2.	**Instalar Dependencias**
   Las librerías principales son: pandas, scikit-learn, seaborn, matplotlib.
3. **Ejecutar el Notebook**

