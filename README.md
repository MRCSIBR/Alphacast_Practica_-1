


# Alphacast Desafío 

> Solucion a Issue: [https://github.com/Leopili1985/Issues/issues/1]

Este repositorio contiene el análisis y transformación de datos del Índice de Precios al Consumidor (IPC) de Argentina, obtenidos del Instituto Nacional de Estadística y Censos (INDEC). 
El objetivo principal es explorar, limpiar y transformar los datos para facilitar su análisis y visualización.

### Descripción del Proyecto

El proyecto se centra en la manipulación de un dataset en formato Excel que contiene los `precios promedio de una selección de alimentos, bebidas y otros artículos de la canasta básica del IPC`, desglosados por regiones y meses desde junio de 2017 hasta noviembre de 2024. El proceso incluye:

1. **Carga de datos**: Descarga del archivo Excel desde la URL proporcionada por el INDEC.
2. **Limpieza de datos**: Eliminación de filas innecesarias, renombrado de columnas y manejo de valores faltantes.
3. **Transformación de datos**: Conversión del formato ancho (wide format) a formato largo (long format) para facilitar el análisis.


### Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **Pandas**: Para la manipulación y análisis de datos.
- **Requests**: Para la descarga del archivo Excel desde la web.
- **Regex**: Para la limpieza y renombrado de columnas.


### Estructura del Repositorio

- **Alphacast_desafio.ipynb**: Notebook de Jupyter que contiene todo el código y análisis.
- **Output_IPC.csv**: Archivo CSV generado a partir del dataset limpio y transformado.

## Cómo Usar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/MRCSIBR/Alphacast_Practica_1.git

2. Instalacion libreria Alphacast
   ```bash
   pip install alphacast   
