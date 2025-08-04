# SegundaParteChallengeTelecom
# Análisis de Cancelación de Clientes (Churn Prediction)

Este proyecto tiene como objetivo identificar los factores que influyen en la cancelación de clientes y construir modelos predictivos que permitan anticipar el abandono. Utiliza datos del conjunto **Telco Customer Churn** y aplica técnicas de machine learning para evaluar el rendimiento de distintos algoritmos.

---

## Variables utilizadas

- `SeniorCitizen`: Indica si el cliente es adulto mayor.
- `tenure`: Tiempo en meses que el cliente ha estado con la empresa.
- `MonthlyCharges`: Monto mensual que paga el cliente.
- `Churn`: Variable objetivo (Sí/No).

---

## Modelos aplicados

- **Random Forest**: Modelo de árboles de decisión en conjunto.
- **XGBoost**: Modelo de boosting eficiente.
- **SVM**: Clasificador basado en márgenes óptimos.

---

## Métricas de evaluación

- Exactitud (Accuracy)
- Precisión
- Recall
- F1-score
- Matriz de confusión

---

## Principales hallazgos

- Clientes con **MonthlyCharges altos** tienen mayor probabilidad de cancelar.
- Clientes con **baja antigüedad (`tenure`)** son más propensos al abandono.
- La variable `SeniorCitizen` tiene menor impacto directo, pero puede influir en combinación con otras.

---

## Cómo ejecutar el proyecto

1. Clona el repositorio o descarga los archivos.
2. Asegúrate de tener instalado Python 3 y las librerías
