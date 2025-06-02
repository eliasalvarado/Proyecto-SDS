# Proyecto-SDS

# 🕵️‍♂️ Detección de Fraude en Comercios con Historial Riesgoso

Este proyecto tiene como objetivo desarrollar un modelo de detección de fraude financiero enfocado específicamente en transacciones realizadas en **comercios con historial riesgoso**. Utilizando técnicas de ingeniería de características, modelos de Gradient Boosting (LightGBM) y funciones de evaluación personalizadas, se optimizó la sensibilidad del modelo en este subconjunto crítico del dataset. 

Se diseñaron tres funciones personalizadas como objetivos de entrenamiento: *recall en comercios riesgosos*, *F1-score penalizado* y *costo ponderado de errores*. La función de **recall en comercios riesgosos** fue la más efectiva, alcanzando un **93.83% de recall** en ese segmento, con un **ratio de falsos positivos de apenas 1.61**. Estas métricas demuestran la eficacia del enfoque personalizado para objetivos específicos del negocio.

## ⚙️ Librerías Utilizadas

Este proyecto fue desarrollado en Python 3.10 y utiliza las siguientes bibliotecas:

- **pandas**: Manipulación y análisis de datos tabulares  
- **numpy**: Operaciones numéricas eficientes  
- **matplotlib** y **seaborn**: Visualización de datos  
- **lightgbm**: Implementación eficiente de Gradient Boosting  
- **scikit-learn**: Preprocesamiento, escalamiento, y métricas  
- **joblib**: Serialización de modelos