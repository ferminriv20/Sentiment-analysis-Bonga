# Análisis de sentimientos - La Bonga del Sinú

Este repositorio contiene un análisis exploratorio y de sentimientos aplicado a reseñas del restaurante "La Bonga del Sinú". 

## Contenido

- `Sentimental_analysis_Bonga.ipynb` - Notebook principal con todo el flujo: carga de datos, preprocesamiento, análisis de sentimientos, visualizaciones y conclusiones.
- `data_bonga.xlsx` -  Archivo Excel con las reseñas extraídas de TripAdvisor. Debes añadirlo en la raíz del repositorio antes de ejecutar el notebook.


## Resumen del proyecto

El objetivo es extraer insights sobre la experiencia de los clientes mediante análisis de texto de reseñas públicas. El notebook realiza:

- Limpieza y preprocesamiento de texto (tokenización, eliminación de puntuación y stopwords en español e inglés).
- Clasificación de sentimientos usando un modelo preentrenado (nlptown/bert-base-multilingual-uncased-sentiment) a través de la librería `transformers`.
- Cálculo de métricas como CSAT estimado, distribución de sentimientos, nubes de n-gramas y análisis por tipo de asistencia.


Te invito a  leer  el notebbook para una explicación mas detallada.
