# Challenge de Data Science de Mercado Libre

## Objetivo
Abordar un caso de negocio, desde el entendimiento del problema hasta la creación de una solución analítica

## Caso de negocio
El equipo comercial quiere realizar estrategias focalizadas para los sellers, pero en
este momento no existe una clasificación que permita identificar a aquellos que tienen
un buen perfil y son relevantes para el negocio. ¿Cómo podrías ayudar al equipo
comercial a identificar estos sellers?

## Estructura del repositorio

El repositorio se encuentra organizado en notebooks de trabajo
1. ETL_sellers: contiene la conexión a la API de Mercado Libre y la extracción de los datos.
2. DataPrep: se crean variables y se agrupan los datos por sellers para continuar el proceso.
3. EDA: se exploran los datos y se extraen los insights
4. clasification: se proponen las soluciones de negocio y se extraen los resultados

## Data
En la carpeta data se encuentran los set de datos de items, sellers y el resultado de la solucion

## Tablero
https://ibelogi.github.io/meli_challengeDS/tablero.html

### Comentarios para replicar el proceso
Al trabajar con los items de Mercado Libre Argentina, se entiende que estos tienen variaciones diarias por bajas de items o modificaciones en el orden de las paginas, por lo tanto para obtener los mismos resultados se debe definir el día en que se extrajeron los datos por primera vez (18-03-2022) de lo contrario los resultados pueden diferir a los realizados en el marco del challenge. 
