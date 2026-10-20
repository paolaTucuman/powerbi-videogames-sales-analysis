# Datos del ejercicio

`ventas_videojuegos.xlsx` es el archivo entregado por el docente del módulo de Power BI para este ejercicio. Contiene una hoja, `Ventas Videojuegos`, con 16.326 registros y diez columnas. Cada fila representa un videojuego en una plataforma; un mismo título puede aparecer en más de una plataforma.

| Columna del Excel | Significado en el ejercicio |
| --- | --- |
| `Nombre` | Título del videojuego. |
| `Plataforma` | Plataforma de lanzamiento. |
| `Año` | Año de lanzamiento. |
| `Genero` | Género del videojuego. |
| `Editorial` | Empresa editora. |
| `Estados Unidos`, `España`, `Japón`, `Brasil` | Rótulos geográficos conservados del archivo del curso; valores numéricos en millones de copias. |
| `Total` | Ventas mundiales en millones de copias. |

Las primeras filas y las variables numéricas coinciden con el conjunto público [Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales), en el que las cuatro columnas regionales se denominan `NA_Sales`, `EU_Sales`, `JP_Sales` y `Other_Sales`. Por ello, los rótulos `Estados Unidos`, `España` y `Brasil` del archivo del curso **no permiten interpretar esas cifras como ventas de esos países**. El archivo se conserva como se utilizó en el ejercicio.

El conjunto de referencia incluye videojuegos con ventas superiores a 100.000 copias y no representa de manera exhaustiva todos los lanzamientos del mercado. El año indica el lanzamiento, no la fecha de cada venta.
