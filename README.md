# Telecom-Analysis: Segmentación y Comportamiento del Usuario

## 📋 Descripción del Proyecto
Este proyecto tiene como objetivo identificar **patrones de uso, comportamientos atípicos y la segmentación de clientes** para comprender las necesidades reales de los usuarios. El análisis permite contrastar el consumo efectivo frente a las características de los planes contratados, facilitando la toma de decisiones estratégicas.

## 📊 Fuentes de Datos
El análisis se basa en la integración de tres conjuntos de datos:
* **`plans.csv`**: Detalles de la oferta comercial (precios, minutos/GB incluidos y tarifas por excedentes).
* **`users_latam.csv`**: Información demográfica (edad, ciudad, fecha de registro y plan).
* **`usage.csv`**: Registros de actividad real (duración de llamadas y volumen de mensajes).

## 🚀 Metodología
El proyecto se desarrolló siguiendo un flujo de trabajo estructurado en 7 etapas:

1.  **Carga y Exploración Inicial:** Diagnóstico de la estructura de las bases de datos.
2.  **Identificación de Calidad:** Detección de valores nulos, duplicados e inconsistencias técnicas.
3.  **Limpieza de Datos:** Tratamiento de errores y preparación de los datasets para el análisis.
4.  **Análisis Estadístico:** Revisión de medidas clave de tendencia central y dispersión en variables categóricas y numéricas.
5.  **Visualización de Datos:** Creación de gráficos para identificar patrones de consumo, sesgos y tendencias.
6.  **Segmentación de Clientes:** Clasificación de usuarios según sus perfiles de necesidad y uso.
7.  **Conclusiones y Recomendaciones:** Síntesis de hallazgos y propuestas de optimización de servicios.

## 📂 Contenido del Repositorio
* `Telecom_Analysis.ipynb`: Notebook con el desarrollo completo paso a paso, visualizaciones e *insights* generados en cada etapa.
* `/data`: Carpeta con los archivos CSV utilizados (si aplica).

---
**Sugerencia de uso:** Para reproducir el análisis localmente, asegúrate de contar con las librerías `pandas`, `seaborn` y `matplotlib` instaladas.
