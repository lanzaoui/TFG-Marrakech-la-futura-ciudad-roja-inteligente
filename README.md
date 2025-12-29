# Análisis del potencial solar urbano en Marrakech

Este repositorio contiene el notebook de Google Colab y los datos necesarios para estimar el potencial solar urbano en Marrakech, basado en el análisis de tejados mediante archivos vectoriales (`.shp`) y raster (`.tiff`).  

## Objetivo del proyecto

El objetivo principal es determinar la superficie de tejados disponible para la instalación de paneles solares y estimar la capacidad de generación fotovoltaica potencial.  

Este análisis permite:  
- Identificar el área útil de los tejados.  
- Calcular la potencia máxima instalable y la energía anual generada estimada.  
- Evaluar la viabilidad técnica de un despliegue solar distribuido en la ciudad.  

> Nota: Aunque el proyecto se plantea en el contexto de Smart Cities, el notebook y los datos se centran únicamente en el análisis de tejados y potencial solar. No incluye la implementación de redes IoT ni otras aplicaciones energéticas.

## Contenido del repositorio

- `TFG_Marrakech_Solar.ipynb`: Notebook de Google Colab con el flujo completo de análisis.   
- `README.md`: Este archivo.
- Los archivos .tiff y .shp necesarios para ejecutar el notebook están disponibles en Hugging Face Hub: https://huggingface.co/datasets/lanzaoui/buildings/tree/main

## Requisitos

- Google Colab (recomendado)  
- Librerías de Python:
  - `geopandas`
  - `rasterio`
  - `matplotlib`
  - `numpy`
  - `pandas`

> Todas las librerías se pueden instalar directamente en Colab si no están presentes.

## Aviso sobre visualización de mapas interactivos

Algunas celdas del notebook generan mapas interactivos con GeoPandas.  
- GitHub no ejecuta notebooks, por lo que los mapas interactivos **no se visualizan directamente**.  
- Para ver correctamente los mapas y resultados interactivos, se recomienda abrir el notebook en Google Colab y ejecútalo.  
- Las figuras estáticas (gráficos PNG) sí se visualizan en GitHub sin problemas.

