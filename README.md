# Proyecto World Happiness

## 1. Definición del Problema
En un contexto en que los índices de desarrollo se analizan desde múltiples perspectivas, la felicidad se ha convertido en un indicador complementario para medir el bienestar de la sociedad. Entender qué factores contribuyen a la felicidad permite priorizar políticas públicas y recursos para maximizar el bienestar general.

### Pregunta de Investigación
**¿Qué factores están más asociados con los niveles de felicidad en los distintos países del mundo entre 2015 y 2019?**

### Métricas de Éxito
- Puntaje promedio de felicidad por año y región.
- Correlación entre las variables independientes y el puntaje de felicidad.
- Análisis de regresión para predecir el puntaje de felicidad.
- Compración entre regiones y cambios en el tiempo.

## 2. Fuentes de Datos
- **Dataset:** World Happiness Report
- **Format:** CSV
- **Tamaño:** Aproximadamente 1.500 filas distribuidas en archivos por año (2015-2019), con al menos 12 columnas cada uno.
- **Origen:** Kaggle - https://www.kaggle.com/datasets/unsdsn/world-happiness?resource=download

## 3. Exploración
El notebook `exploracion.ipynb` contiene el código para:
1. Descargar y combinar los archivos anuales en un solo CSV.
2. Generar un reporte de exploración con `pandas_profiling`.
3. Visualizar duplicados, valores nulos, tipos de datos, distribuciones y correlaciones.
