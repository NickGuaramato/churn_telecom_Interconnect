# Predicción de Tasa de Abandono de Clientes en Telecom Interconnect

Este proyecto, a través de pipelines que mejoran el flujo de trabajo, busca entre varios modelos de aprendizaje automático con la intención de observar el comportamiento y efectividad de cada uno de ellos para luego proceder a entrenar el más óptimo según lo arrojado por las respectivas métricas que evalúan la calidad del mismo, esto con la intención de que pueda predecir la probabilidad de abandono de clientes en una empresa de telecomunicaciones de manera objetiva y confiable. Mediante el análisis de datos de clientes y contratos, se busca identificar aquellos con mayor riesgo de dejar el servicio.

## Outputs del Proyecto

El proyecto genera varios outputs importantes que se guardan en la carpeta `outputs/`:
- **Datos Preprocesados**: Carpeta donde se almacenan los datos una vez hecho el respectivo encodificado y escalado.
- **Modelos Entrenados**: Los mejores modelos entrenados se guardan en `outputs/models/`. Esto permite cargar los modelos para hacer predicciones sin tener que volver a entrenarlos.
- **Gráficas ROC**: Las gráficas ROC de cada modelo se almacenan en `outputs/plots/`. Estas gráficas permiten visualizar el rendimiento de cada modelo en términos de sus tasas de verdaderos positivos y falsos positivos.
- **Reportes de Clasificación**: Los reportes de clasificación, que incluyen precisión, recall y F1-score para cada clase, se guardan en `outputs/reports/`. Cada archivo contiene el reporte de clasificación de un modelo específico.
- **Métricas de Evaluación**: El archivo `outputs/metrics/model_metrics.csv` contiene las métricas de AUC-ROC para todos los modelos, facilitando la comparación de su rendimiento.