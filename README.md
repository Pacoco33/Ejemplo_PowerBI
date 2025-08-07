# Análisis de Ventas de Videojuegos con Power BI

Este proyecto consiste en la transformación, modelado y visualización de un conjunto de datos de ventas de videojuegos a nivel mundial. Ha sido desarrollado como parte de una práctica de análisis con Power BI, utilizando técnicas de limpieza con Power Query, visualización interactiva y segmentación avanzada. Realizado en el módulo "Big Data" del Curso de Especialización "IA y Big Data".

## Objetivo del Proyecto

Analizar la evolución de las ventas de videojuegos a lo largo del tiempo, por región, género, plataforma y título, con el fin de obtener conclusiones relevantes sobre el comportamiento del mercado global.

## Contenido del Repositorio

- `videosales.pbix`: Archivo principal del reporte de Power BI.
- `vgsales.xlsx`: Fuente de datos original en formato Excel.
- `videosales.pdf`: Exportación del dashboard como documento PDF.
- `README.md`: Descripción completa del proyecto.
- `Transformación y visualización de datos con Power Query - Paco Cabrerizo.pdf`: Manual-guía elaborado por mí como soporte para el proceso de transformación y visualización de datos en Power BI.
  
## Proceso de Transformación de Datos

La limpieza y transformación de datos se llevó a cabo en Power Query, incluyendo los siguientes pasos:

- Eliminación de columnas no relevantes como `Rank` y `Global Sales`.
- Desanidamiento de las columnas de ventas por región (`NA_Sales`, `EU_Sales`, `JP_Sales`, `Other_Sales`) para generar un modelo más analizable.
- Conversión de columnas de ventas en dos nuevas columnas: `Región` y `Ventas`.
- Cambio de nombres de columnas al español (`Name` a `Nombre`, `Platform` a `Plataforma`, etc.).
- Sustitución de nombres de regiones por etiquetas más claras (`NA_Sales` por `Norte América`, etc.).
- Conversión del campo `Año` a texto para evitar sumas o promedios no deseados en visualizaciones.

## Visualizaciones Incluidas

El dashboard final incluye las siguientes visualizaciones:

- Tabla con los títulos más vendidos, incluyendo nombre, plataforma, año y ventas.
- Gráfico de columnas apiladas con las ventas por año y plataforma.
- Gráfico circular para mostrar las ventas por región.
- Treemap para visualizar la distribución de ventas por género.
- Tarjeta resumen con el total de ventas.
- Segmentaciones por año, género, plataforma, editor y región.

## Funcionalidades Interactivas

- Interacción entre todas las visualizaciones (por ejemplo, selección de un juego afecta al resto de los gráficos).
- Filtros dinámicos mediante segmentaciones.
- Resaltado cruzado entre tabla, gráfico de barras, gráfico circular y treemap.

## Herramientas Utilizadas

- Power BI Desktop
- Power Query para limpieza y transformación de datos
- Excel como fuente de datos original
- Exportación del informe en formato PDF
