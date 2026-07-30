# bankruptcy-prediction-ensemble
Notebook que predice bancarrota de empresas usando el dataset "American Companies Bankruptcy Prediction" (Kaggle) ensamblando distintos métodos de ML.

Incluye EDA con detección de outliers y correlaciones (Spearman), preprocesamiento (eliminación de variables redundantes, escalado, manejo de desbalanceo de clases), y entrenamiento de 4 modelos calibrados (Logistic Regression, Random Forest, MLP, SVC) combinados en un ensamble soft-voting ponderado por F2-score. El umbral de decisión se optimiza en validación priorizando recall (minimizar falsos negativos), y el análisis final incluye importancia por permutación para explicar qué variables más afectan la predicción
