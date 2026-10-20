# Ventas de videojuegos | Power BI

<img src="images/company-play-logo.png" alt="Identidad visual Company Play utilizada en el informe" width="150">

El reporte permite explorar el volumen de ventas de videojuegos por género y año de lanzamiento, y conserva la comparación geográfica solicitada en la práctica. El proyecto muestra cómo organicé los indicadores y la navegación para pasar de una vista general al detalle.

## Problema

¿Qué géneros concentran más copias vendidas en el conjunto de videojuegos y cómo puede explorarse su distribución con un informe interactivo?

## Datos

El archivo de trabajo fue entregado por el docente del módulo. Contiene **16.326 registros** de videojuegos por plataforma, con año de lanzamiento entre **1980 y 2017**, género, editorial, cuatro columnas geográficas y total mundial. Las cifras de ventas representan **millones de copias**, no ingresos monetarios. El conjunto corresponde a la estructura de [Video Game Sales, de Gregory Smith](https://www.kaggle.com/datasets/gregorut/videogamesales), basado en datos de VGChartz.

El [diccionario y alcance de los datos](data/README.md) explica las columnas del archivo del curso y cómo interpretar la segmentación geográfica.

## Mi aporte y método

El ejercicio fue guiado, pero construí mi propio informe en Power BI a partir del archivo entregado. Organicé una **portada** con indicadores y navegación y una página de **detalles** con ventas por género, mapa y segmentador por año. El informe usa la medida `Total Ventas` del modelo para alimentar las visualizaciones.

Los recursos gráficos usados en la portada están en [`images/`](images/).

## Resultados

- En el archivo, el género **Action** suma **1.722,88 millones de copias**, por encima de **Sports** (**1.309,24 millones**) y **Shooter** (**1.026,20 millones**).
- La suma de la columna `Total` es **8.820,07 millones de copias** para los registros incluidos en este archivo. Es un acumulado del conjunto, no una cifra de ingresos ni de ventas de una empresa concreta.
- El filtro de año y la navegación entre páginas permiten examinar segmentos específicos sin perder la vista general del informe.

## Características principales

- **Diseño de interfaz:** portada y página de detalle con navegación entre ambas.
- **Indicadores visibles:** tarjetas para el total de ventas y la fecha de actualización del informe.
- **Filtros dinámicos:** segmentador por año de lanzamiento.
- **Visualizaciones analíticas:** comparación por género y mapa geográfico usados en la práctica.

## Tecnologías y habilidades técnicas

- **Power BI Desktop:** construcción del informe, diseño de páginas, visualizaciones y navegación.
- **Power Query:** preparación de los datos utilizados en el modelo del informe.
- **Medidas del modelo:** uso de `Total Ventas` para resumir el volumen de copias en las visualizaciones.
- **Fuente de datos:** libro de Excel entregado para el ejercicio; se incluye en [`data/`](data/README.md).

## Aprendizajes

Aprendí a organizar un informe con navegación y filtros para que la exploración sea más clara. Si repitiera el ejercicio, comprobaría los rótulos geográficos antes de construir el mapa.

## Alcance

El año es el **año de lanzamiento** del videojuego, no necesariamente el año en que se vendieron las copias. Los rótulos geográficos se conservan como aparecen en el archivo del ejercicio; la fuente de referencia agrupa las cifras por Norteamérica, Europa, Japón y otras regiones. Por ello, el mapa forma parte del ejercicio de visualización y **no debe usarse para afirmar ventas por cada país rotulado ni para comparar todos los continentes**.

## Abrir el informe

1. Descargar [`report/Dashboard_Ventas_CompanyPlay.pbix`](report/Dashboard_Ventas_CompanyPlay.pbix) y abrirlo con Power BI Desktop.
2. Si Power BI solicita actualizar la ruta de origen, seleccionar [`data/ventas_videojuegos.xlsx`](data/ventas_videojuegos.xlsx).
3. Explorar la portada y la página de detalles. El archivo de datos conserva los encabezados usados en la práctica.
