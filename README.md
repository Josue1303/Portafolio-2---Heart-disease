# Portafolio 2 Heart disease
## Conjunto de datos obtenidos de: https://www.kaggle.com/datasets/krishujeniya/heart-diseae/data

# Análisis y Reporte sobre el Desempeño del Modelo de Regresión Logística

Este repositorio contiene el análisis y reporte completo del desempeño de un modelo de regresión logística para predecir la presencia de enfermedades cardíacas, utilizando un conjunto de datos clínicos. El análisis incluye evaluaciones detalladas del modelo sin ajustes y con ajustes, utilizando técnicas de validación cruzada y regularización para mejorar su rendimiento.


## Contenido del Análisis

1. **Introducción**: Descripción general del problema, el conjunto de datos y los objetivos del análisis.
2. **Descripción del Conjunto de Datos**: Información detallada sobre las variables presentes en el conjunto de datos.
3. **Elección de Features**: Proceso de selección de las características más relevantes para mejorar el modelo. Esta sección puede omitirse si solo se desea revisar el análisis centrado en las subcompetencias del módulo.
4. **Separación y Evaluación del Modelo con un Conjunto de Prueba y un Conjunto de Validación (Train/Test/Validation)**: Metodología utilizada para dividir los datos y evaluar el rendimiento del modelo.
5. **Evaluación de la Regresión Logística sin Ajustes**: Análisis del rendimiento del modelo antes de aplicar técnicas de regularización y optimización de hiperparámetros.
6. **Diagnóstico y Explicación del Grado de Sesgo (Bias): Bajo, Medio, Alto**: Evaluación del nivel de sesgo del modelo, con explicaciones basadas en los resultados obtenidos.
7. **Diagnóstico y Explicación del Grado de Varianza: Bajo, Medio, Alto**: Análisis de la capacidad del modelo para generalizar a nuevos datos.
8. **Diagnóstico y Explicación del Nivel de Ajuste del Modelo: Underfitting, Fitting, Overfitting**: Evaluación del nivel de ajuste del modelo y su capacidad para evitar errores comunes en el aprendizaje automático.
9. **Técnicas de Regularización o Ajuste de Parámetros para Mejorar el Desempeño del Modelo**: Descripción de las técnicas de optimización de hiperparámetros y regularización utilizadas para mejorar el modelo.
10. **Evaluación de la Regresión Logística con Ajustes**: Análisis del rendimiento del modelo después de aplicar técnicas de regularización (`l2`) y optimización de hiperparámetros mediante `GridSearchCV`.
11. **Conclusión**: Resumen de los resultados obtenidos y los aprendizajes derivados del proceso de modelado.

## Importante

Si solo te interesa revisar el cumplimiento de las subcompetencias evaluadas, puedes **omitir la sección de "Elección de Features"** en el documento. Esta sección se incluyó para mejorar el modelo lo más posible, considerando únicamente las características importantes del conjunto de datos.

## Herramientas Utilizadas

- **Python**: Para el desarrollo del modelo y análisis de datos.
- **Librerías de Python**: `scikit-learn` para la implementación de modelos de regresión logística y optimización de hiperparámetros, y `pandas` para la manipulación de datos.
- **Visualización de Datos**: Gráficos generados con `matplotlib` y `seaborn` para interpretar el desempeño del modelo.
