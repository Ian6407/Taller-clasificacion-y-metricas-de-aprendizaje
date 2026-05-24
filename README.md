# Clasificación y Métricas de Aprendizaje — Dataset Bancario
 
**Estudiante:** Ian Tomas Felipe Fonseca Coronado  
**Universidad:** Pontificia Universidad Javeriana  
**Materia:** Procesamiento de Alto Volumen de Datos  
 
---
 
## Descripción
 
Este proyecto aplica modelos de clasificación sobre el dataset de campañas de marketing telefónico de un banco portugués, con el objetivo de predecir si un cliente se suscribirá o no a un depósito a plazo. Todo el procesamiento se realizó con **PySpark** sobre un clúster distribuido.
 
---
 
## Flujo del Análisis
 
1. **Importación y configuración** de bibliotecas y sesión Spark
2. **Análisis exploratorio** de variables y tipos de datos
3. **Visualizaciones** de distribución de variables clave
4. **Limpieza de datos** y eliminación de outliers
5. **Feature Engineering** y construcción del Pipeline
6. **División** del dataset en entrenamiento (80%) y prueba (20%)
7. **Entrenamiento y evaluación** de dos modelos:
   - Regresión Logística
   - Árbol de Decisión
8. **Comparación** de modelos por Accuracy, F1-Score y ROC
---
 
## Resultados
 
| Modelo | Accuracy | F1-Score | ROC |
|---|---|---|---|
| Regresión Logística | 81.3% | 81.3% | 0.89 |
| Árbol de Decisión | 80.1% | 80.1% | 0.63 |
 
 **Modelo recomendado:** Regresión Logística
 
---
 
## Cómo Ejecutar
 
1. Clonar el repositorio
2. Asegurarse de tener Spark configurado y corriendo
3. Colocar el archivo `bank-full.csv` en el directorio raíz
4. Ejecutar el cuaderno `TallerFonsecaClasificacion.ipynb`
---
 
## Dataset
 
Fuente: [UCI Machine Learning Repository — Bank Marketing](https://archive.ics.uci.edu/dataset/222/bank+marketing)
