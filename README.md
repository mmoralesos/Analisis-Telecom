# Analisis-Telecom
Se realiza un análisis a la data de Telecom para generar informe analítico
# 📊 Telco Churn Analysis

Este proyecto analiza un conjunto de datos de una empresa de telecomunicaciones para identificar patrones de abandono (churn), uso de servicios, ingresos y fidelización del cliente.

## 🧾 Contenido

- Lectura directa desde un archivo JSON en línea
- Expansión y limpieza de columnas anidadas
- Transformación y conversión de tipos de datos
- Análisis de servicios más contratados
- Visualización de churn por tipo de contrato y método de pago
- Análisis de ingresos y permanencia promedio
- Correlaciones entre variables numéricas
- Exportación de gráficos en formato PNG para informes y presentaciones

## 📁 Archivos

- `telco_churn_analysis.py`: Script principal del análisis y generación de visualizaciones.
- Gráficos exportados como `.png` en el mismo directorio.

## 📊 Ejemplos de visualizaciones

- Cantidad de servicios contratados
- Churn por tipo de contrato
- Distribución de cargos totales según churn
- Permanencia promedio por servicio contratado
- Churn según método de pago
- Mapa de calor de correlaciones entre variables numéricas
- Boxplot de cargos mensuales por tipo de contrato

## ▶️ Cómo ejecutar

1. Instala las dependencias:

```bash
pip install pandas seaborn matplotlib
