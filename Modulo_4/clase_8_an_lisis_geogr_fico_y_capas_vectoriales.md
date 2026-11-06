---
title: "Notas de Clase: Análisis Geográfico y Capas Vectoriales en QGIS"
date: "`r Sys.Date()`"
output: html_document
---

## Resumen Ejecutivo

En esta sesión abordamos el uso práctico de QGIS enfocado en la manipulación de insumos satelitales GeoTIFF y la generación de geometrías vectoriales (puntos y polígonos). Aplicamos estos conceptos en un caso práctico enfocado en el monitoreo de la cubierta de nieve en los Andes centrales, tomando como área de estudio el Glaciar de las Lágrimas (departamento de Malargüe, Mendoza), sitio donde tuvo lugar el accidente aéreo de los deportistas uruguayos en 1972.

## Manejo de Insumos Satelitales y GeoTIFF

* **QGIS como herramienta principal:** Se utilizó este software de código abierto por su flexibilidad en el tratamiento de datos espaciales.
* **Estructura del formato GeoTIFF (`.tif` / `.tiff`):** Este estándar almacena la información de georreferenciación en los propios encabezados del archivo, permitiendo trabajar con capas ráster de manera directa sin depender de archivos de soporte externos (como los *world files*).
* **Adquisición de datos:** Las imágenes multiespectrales se descargaron desde la plataforma Copernicus Browser (misión Sentinel-2), seleccionando exclusivamente tomas con una cobertura de nubes inferior al 10 % para asegurar la visibilidad del terreno.

## Generación de Vectores y Delimitación de Superficies

Para calcular áreas precisas en unidades métricas ($m^2$), el entorno de trabajo se configuró bajo un sistema proyectado adecuado para la franja geográfica correspondiente.

* **Sistema de Coordenadas de Referencia (SRC):** Se fijó en **UTM Zona 19S / WGS 84** (`EPSG:32719`).
* **Delimitación de áreas:** Mediante edición manual sobre un archivo de almacenamiento GeoPackage, se trazó el contorno del manto de nieve delimitando punto a punto la geometría del polígono.