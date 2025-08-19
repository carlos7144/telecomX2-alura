Proyecto de Predicción de Cancelación de Clientes (Churn)

📌 Este proyecto utiliza Machine Learning para predecir la cancelación de clientes en una empresa de telecomunicaciones. A través de análisis exploratorio, modelado con KNN y Random Forest, y evaluación de métricas de desempeño, se identifican los factores más relevantes en la decisión de abandono y se proponen estrategias de retención. 🚀

📑 Tabla de Contenidos

Descripción del Proyecto

Estructura del Proyecto

Metodología

Resultados de Modelos

Principales Factores de Cancelación

Estrategias de Retención Propuestas

Próximos Pasos

Autor

📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar y predecir la cancelación de clientes (churn) en una empresa de telecomunicaciones. A través de técnicas de Machine Learning y análisis exploratorio de datos, se busca identificar los principales factores que influyen en el abandono de clientes y proponer estrategias de retención.

📂 Estructura del Proyecto

notebooks/ → Contiene el notebook principal (telecomX2.ipynb) con todo el proceso de análisis y modelado.

data/ → Incluye el dataset procesado (df_plano.csv).

reports/ → Documentación e informes con resultados y conclusiones.

🔍 Metodología

Exploración de Datos (EDA): Limpieza, análisis de variables y visualización de correlaciones.

Preprocesamiento: Transformación de variables categóricas, normalización y división en train/test.

Modelado: Entrenamiento de modelos KNN y Random Forest.

Evaluación: Cálculo de métricas de desempeño (Accuracy, Precision, Recall, F1-score).

Interpretación: Análisis de importancia de variables en Random Forest.

Conclusiones: Identificación de factores clave y recomendaciones estratégicas.

📊 Resultados de Modelos

K-Nearest Neighbors (KNN):

Accuracy: 0.74

Precision (churn): 0.58

Recall (churn): 0.52

F1-score (churn): 0.55

Random Forest:

Accuracy: 0.78

Precision (churn): 0.60

Recall (churn): 0.46

F1-score (churn): 0.52

➡️ Random Forest mostró un mejor rendimiento general que KNN, aunque ambos modelos presentaron dificultades para identificar clientes que cancelan (recall bajo).

📌 Principales Factores de Cancelación

Altos cargos facturados (account.Charges.Total)

Baja permanencia (customer.tenure)

Tipo de contrato (contract.Type), especialmente contratos mensuales.

Servicios de internet y telefonía (internet.Service, phone.PhoneService)

💡 Estrategias de Retención Propuestas

Programas de fidelización para clientes nuevos.

Planes tarifarios flexibles y personalizados.

Promoción de contratos a largo plazo con beneficios adicionales.

Optimización de servicios clave (internet y telefonía).

Monitoreo preventivo de clientes en riesgo con alertas tempranas.

🚀 Próximos Pasos

Aplicar técnicas de balanceo de datos (Oversampling/SMOTE) para mejorar recall.

Probar modelos más avanzados como XGBoost o LightGBM.

Integrar el modelo en un sistema de alerta temprana para retención proactiva.

👨‍💻 Autor

Proyecto desarrollado por Carlos Martínez como parte de un análisis aplicado de Machine Learning en telecomunicaciones.


