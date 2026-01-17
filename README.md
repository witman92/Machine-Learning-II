Resumen del Proyecto Final

Machine Learning II

Aplicación de Ciencia de Datos y Machine Learning al Control de Calidad en el Despacho de Pulpas de Fruta Concentrada

Witman Zavala Muñoz

En este proyecto se desarrolló una aplicación de Ciencia de Datos y Machine Learning orientada a apoyar el control de calidad en el proceso de despacho de pulpas de fruta concentrada, con el objetivo de predecir el destino final del producto (liberado o decomisado) a partir de registros históricos del proceso de inspección.

El problema se formuló como una tarea de clasificación supervisada binaria, donde la variable objetivo corresponde al destino del producto. El dataset incluye variables numéricas y categóricas asociadas a defectos, condiciones operacionales y características del proceso. Se realizó un análisis exploratorio de datos que permitió identificar desbalance de clases y relaciones no lineales relevantes.

El preprocesamiento fue implementado mediante un Pipeline, con el fin de evitar fuga de información y garantizar consistencia entre entrenamiento y evaluación. Se aplicó imputación constante para variables numéricas y codificación One-Hot Encoding para variables categóricas. Se entrenaron y compararon modelos basados en árboles y boosting (Random Forest, LightGBM y XGBoost), utilizando Grid Search con validación cruzada. Dado el desbalance de clases, se priorizó el F1-score como métrica principal y se ajustó el umbral de decisión.

La evaluación en el conjunto de prueba mostró que XGBoost obtuvo el mejor desempeño global, con F1-score superior a 0.97, altos valores de AUC y el menor número de Falsos Negativos, aspecto crítico para evitar la liberación de productos defectuosos. Finalmente, se propuso un esquema conceptual de despliegue del modelo como herramienta de apoyo a la toma de decisiones en control de calidad, destacando su potencial para reducir riesgos operativos y mejorar la eficiencia del proceso.
