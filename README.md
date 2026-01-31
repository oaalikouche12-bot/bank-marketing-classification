# Bank Marketing – Client Classification

Proyecto de clasificación supervisada sobre el dataset **Bank Marketing**, con el
objetivo de predecir si un cliente contratará un producto bancario a partir de
variables sociodemográficas y de contacto.

## Objetivo
Construir y evaluar un modelo de clasificación que prediga la variable objetivo
(`y`: suscripción del producto), siguiendo un flujo completo de Machine Learning.

## Dataset
- **bank-full.csv**
- Fuente: Bank Marketing Dataset
- La variable objetivo es `y` (yes/no).

## Metodología
1. Análisis Exploratorio de Datos (EDA)
   - Análisis univariante, bivariante y multivariante
2. Preprocesamiento
   - Tratamiento de variables categóricas
   - One-hot encoding (`get_dummies`)
3. Modelado
   - Regresión Logística
4. Evaluación
   - Accuracy
   - Matriz de Confusión
   - Precision, Recall, F1-score

## Estructura del repositorio
- `bank_marketing_classification.ipynb`: notebook principal del proyecto
- `data/`: carpeta con el dataset

## Uso
Abrir el notebook y ejecutar las celdas en orden. Ajustar la ruta del CSV si es
necesario.
