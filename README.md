# sprint7-final-project
Análisis estadístico de clientes ConnectaTel - Sprint 7
# ConnectaTel Analysis – Sprint 7

Análisis estadístico de clientes de una empresa de telecomunicaciones 
con operaciones en México y Colombia.

## 🎯 Objetivo

Identificar patrones de uso, detectar comportamientos atípicos y 
comprender qué segmentos de clientes muestran necesidades diferenciadas,
con el fin de optimizar la oferta comercial de ConnectaTel.

## 📂 Contenido del repositorio

- `connectatel_analysis.ipynb` → Notebook principal con limpieza, 
  EDA, distribuciones, outliers, segmentación y conclusiones ejecutivas.

## 📊 Datasets utilizados

| Archivo | Descripción |
|---------|-------------|
| `plans.csv` | Catálogo de planes Básico y Premium |
| `users_latam.csv` | Información de 4,000 clientes |
| `usage.csv` | 40,000 registros de llamadas y mensajes |

## 🔍 Etapas del análisis

1. Carga y exploración de los 3 datasets
2. Identificación de problemas de calidad (nulos, sentinels, fechas)
3. Limpieza básica de datos
4. Summary statistics por usuario
5. Visualización de distribuciones y outliers
6. Segmentación por edad y nivel de uso
7. Insight ejecutivo con recomendaciones comerciales

## 📋 Guía de reproducción

1. Clona o descarga este repositorio
2. Asegúrate de tener instaladas las siguientes librerías:
   - pandas
   - numpy
   - seaborn
   - matplotlib
3. Coloca los archivos `plans.csv`, `users_latam.csv` y `usage.csv` 
   en la carpeta `/datasets/`
4. Abre el notebook `S7 Version-Estudiante-Project-ConnectaTel.ipynb`
5. Ejecuta las celdas en orden desde la primera hasta la última
6. Los resultados, gráficos y conclusiones se generan automáticamente

## ▶ Cómo ejecutar el notebook

1. Descarga el archivo `connectatel_analysis.ipynb`
2. Ábrelo en Jupyter Notebook
3. Ejecuta las celdas en orden
4. Los datasets deben estar en `/datasets/`
