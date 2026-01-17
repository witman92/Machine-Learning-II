Resumen del Proyecto Final

Machine Learning II

Aplicación de Ciencia de Datos y Machine Learning al Control de Calidad en el Despacho de Pulpas de Fruta Concentrada

Witman Zavala Muñoz
Curso Machine Learning II

En este proyecto se desarrolló una aplicación de Ciencia de Datos y Machine Learning orientada a apoyar el control de calidad en el proceso de despacho de pulpas de fruta concentrada, con el objetivo de predecir el destino final del producto, ya sea aprobación para despacho o decomiso, a partir de información histórica del proceso de inspección.

El problema fue formulado como una tarea de aprendizaje supervisado de clasificación binaria, donde la variable objetivo corresponde al destino del producto. El conjunto de datos incluye variables numéricas y categóricas asociadas a características de calidad, defectos detectados y variables operacionales del proceso productivo. Se realizó un análisis exploratorio de datos (EDA) que permitió identificar patrones relevantes, desbalance de clases, valores atípicos y relaciones preliminares entre las variables y el destino final del producto.

Posteriormente, se llevó a cabo un proceso sistemático de preprocesamiento de datos, que incluyó la validación de tipos de datos, tratamiento de valores faltantes, codificación de variables categóricas y escalamiento de variables numéricas, además de la correcta separación de los conjuntos de entrenamiento y prueba, siguiendo buenas prácticas en Machine Learning.

Se entrenaron y compararon distintos modelos de clasificación supervisada, incluyendo Regresión Logística, Árbol de Decisión y Random Forest, utilizando Grid Search con validación cruzada para el ajuste de hiperparámetros. La evaluación de los modelos se realizó mediante métricas estándar de clasificación como accuracy, precision, recall y F1-score, permitiendo una comparación objetiva de su desempeño.

Los resultados mostraron que los modelos basados en árboles presentan un mejor desempeño global en la predicción del destino del producto, logrando un equilibrio adecuado entre la detección de productos susceptibles a decomiso y la minimización de errores de clasificación. Finalmente, se discutieron las principales limitaciones del enfoque, asociadas principalmente al desbalance de clases y la variabilidad del proceso, y se propuso un esquema conceptual de despliegue del modelo como herramienta de apoyo a la toma de decisiones en el área de control de calidad, enfatizando su uso como complemento al criterio humano y no como sistema automático de decisión.
