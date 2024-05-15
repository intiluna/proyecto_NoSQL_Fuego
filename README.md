# Proyecto de Demostración de NoSQL y Modelado de Datos con MongoDB

Este proyecto demuestra el uso de MongoDB para gestionar datos relacionados con la detección de incendios forestales a partir de datos de satélite MODIS Terra/Aqua. Se simula el escenario de un centro de investigación ambiental que requiere una infraestructura eficiente para almacenar y analizar datos.

## Contexto

En este proyecto, se emplea MongoDB para modelar y gestionar datos provenientes de múltiples fuentes, como datos de satélite MODIS, límites de países, datos de gobiernos y reportes de eventos. La estructura de los datos puede variar y evolucionar con el tiempo.

## Requerimientos del Sistema

Para ejecutar este proyecto, necesitarás:

- MongoDB 
- Python 3
- Datos a descargar en: "https://drive.google.com/drive/folders/1ustCKZTFa43lTiO8X_H_8PCr5zHWhzzv?usp=sharing"
- Bibliotecas de Python: pymongo, pandas, numpy,pathlib, matplotlib, datetime, time,json, folium



## Configuración del Proyecto

1. Clona este repositorio en tu máquina local.
2. Asegúrate de tener MongoDB en ejecución en tu sistema.
3. Ejecuta el notebook `clean_preprocess_fire.ipynb` para realizar el preprocesamiento de los datos.
4. Ejecuta el notebook `Proyecto_NoSQL_IntiLuna.ipynb` para realizar inserción, creación de índices y consultas.

## Estructura de los Datos

Los datos se modelan utilizando documentos en MongoDB, lo que permite manejar datos variables y esquemas flexibles. Los documentos representan registros de detección de incendios e incluyen información sobre coordenadas, intensidad, satélite y otros campos relevantes.

## Contribuciones

¡Las contribuciones son bienvenidas! Si tienes sugerencias de mejoras, correcciones de errores o deseas agregar nuevas funcionalidades, no dudes en enviar una solicitud de extracción.
