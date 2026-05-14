# Análisis de Juegos de Steam 2025 🎮

Dashboard de análisis del catálogo de juegos disponibles en Steam durante 2025,
construido con Power Query y DAX en Power BI.

## Herramientas

Power Query · DAX · Power BI

## Dataset

Dataset extraído de Kaggle con información de 723 juegos disponibles en Steam en 2025,
incluyendo precios, géneros, publicadores, compatibilidad de plataformas, horas jugadas,
puntajes Metacritic y reseñas de la comunidad.

## Contenido

- Modelo de datos relacional con tablas de hechos y dimensiones (JUEGOS, GÉNEROS, PUBLICADORES, DESARROLLADORES, CALENDARIO)
- Transformaciones y limpieza de datos en Power Query
- Métricas DAX: totales, promedios, porcentajes de compatibilidad y medidas contexto-aware
- Dashboard interactivo de 4 páginas con navegación, filtros por período y publicador
- Glosario de términos y definiciones del modelo

## Estructura del dashboard

- **Global**: KPIs generales, top 5 géneros y top 5 publicadores por cantidad de juegos
- **Intermedio**: Evolución temporal de lanzamientos, promedio de horas jugadas por género y distribución por publicador
- **Detalle**: Top 10 juegos con más DLCs, compatibilidad por plataforma y relación precio vs calidad
- **Glosario**: Definición de métricas, dimensiones y tablas del modelo

## Principales hallazgos

- Los juegos mejor valorados por Metacritic se concentran en el rango de USD 0 a USD 20, sugiriendo que el precio alto no garantiza calidad percibida
- Action, Adventure e Indie son los géneros con mayor presencia en el catálogo, representando más del 60% de los títulos
- El pico de lanzamientos se registró entre 2015 y 2020, con una caída sostenida hacia 2025
- Massively Multiplayer y Free To Play lideran ampliamente en horas jugadas promedio, superando en más del 50% al siguiente género
- Solo el 23,56% de los juegos es compatible con Linux y el 17,89% con Mac, frente al 58,54% exclusivo de Windows
- Electronic Arts lidera en volumen de publicaciones entre los grandes publishers, seguido por Devolver Digital y SEGA
- Dead or Alive 6 concentra la mayor cantidad de DLCs con 461, más del doble que el segundo título
