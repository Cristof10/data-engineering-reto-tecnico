# Prueba Técnica – Data Engineer

Solución a una prueba práctica de ingeniería de datos desarrollada en Google Colab. El notebook incluye el código y las salidas de cada ejercicio.

**Autor:** Cristofer Paucar

## Contenido

- **SQL (SQLite):** consultas sobre una simulación del Mundial Qatar 2022 con funciones de ventana (`ROW_NUMBER`, `NTILE`) para obtener los clasificados por grupo, sus sedes y los equipos élite.
- **PySpark:** ranking de goleadores por país con un nuevo indicador de eficiencia (goles/partidos), cálculo del centro educativo más céntrico de Madrid por titularidad con una UDF de distancia euclidiana, y exportación de resultados en Parquet, JSON y CSV.

## Cómo ejecutar

1. Abrir el `.ipynb` en [Google Colab](https://colab.research.google.com/).
2. Subir `CENTROS_EDUCATIVOS_MADRID.json` a `/content`.
3. Ejecutar las celdas en orden.
