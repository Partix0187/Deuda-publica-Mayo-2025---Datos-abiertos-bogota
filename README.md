# Deuda-publica-Mayo-2025---Datos-abiertos-bogota
Se creo un flujo de análisis a partir de fuentes abiertas sobre la deuda pública de Bogotá (mayo 2025). Abarca la carga, limpieza intensiva, generación de agregados por entidad y la exportación de datos listos para BI. Todo el procedimiento se encuentra implementado en un notebook y concluye en la publicación de resultados en Looker Studio.

# Limpieza y Publicación de Deuda Pública Bogotá - Mayo 2025

# Resumen
Este repositorio contiene el flujo completo para la limpieza, estandarización, análisis agregado y publicación visual de los datos de deuda pública para la ciudad de Bogotá al mes de mayo de 2025. El pipeline parte de un dataset abierto proporcionado por la Alcaldía y finaliza en un dashboard visual en Looker Studio.

# Estructura del Proyecto
Deuda_publica_mes_de_Mayo_2025.ipynb – Notebook con cada paso del proceso ETL, limpieza avanzada y agregación de datos.

Deuda_publica_Mayo_2025_-_Datos_abiertos_bogota.pdf – Archivo fuente y referencia del dataset original.

deudatotalporentidadlimpio.csv – Archivo exportado y listo para su uso en BI.

# Flujo de Trabajo
Carga y exploración de los datos originales usando Pandas.

Limpieza estructural: renombramiento y estandarización de columnas y entidades acreedoras.

Transformación numérica: conversión y formateo adecuado de valores económicos.

Filtrado y depuración: se eliminan filas con datos desconocidos y se agrupan las deudas por entidad estandarizada.

Exportación: los datos consolidados y limpios se guardan en CSV.

Publicación y visualización: se carga el archivo limpio en Looker Studio, permitiendo análisis visuales interactivos.

# Tecnologías empleadas
Python (Pandas, Regex)

Jupyter/Colab Notebooks

Google Looker Studio

Enlace a Visualización
Publica el enlace a Looker Studio cuando esté disponible.

Note:

This repository documents the data cleaning, transformation, and visualization process for Bogotá's public debt (May 2025). The final dashboard is available on Looker Studio:
https://lookerstudio.google.com/reporting/6fed48b2-574e-427e-b672-3cb6a47e9d3b

Important note:
All results in this dashboard are presented as totals per company (entity). If you review the original public records, you will notice that debt figures vary by contract. This reflects a crucial reminder: every data analysis is shaped by how the requirements are defined. In this case, the project focused on aggregating total debt per company to meet a specific reporting need. Different questions or requirements will very likely lead to different aggregations and insights.

Please refer to the dashboard and methodology for details or to adapt this pipeline for other analytical perspectives

Contribuciones
Sugerencias y mejoras son bienvenidas. Utiliza Issues para reportar errores o Pull Requests para contribuir.
