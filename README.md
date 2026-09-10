# Movilidad urbana y productividad económica en ciudades latinoamericanas

Este repositorio contiene el análisis realizado durante el Sprint 5. El objetivo es **evaluar cómo la movilidad urbana se relaciona con la productividad económica en las principales ciudades latinoamericanas**. 

El análisis se basa en datos reales de TomTom Traffic Index y OECD Cities. El siguiente proceso demuestra la limpieza, unión y análisis de los datos para identificar en qué ciudades conviene invertir en infraestructura de transporte.

## Contenido del repositorio

- `S5 ladb_mobility_economy_project_student.ipynb`
  → Notebook principal con limpieza, unión de dos dataframes distintos, visualizaciones, análisis y conclusiones.

## Cómo reproducir el análisis

1. Abrir `S5 ladb_mobility_economy_project_student.ipynb`
2. Ejecutar las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## Objetivo del análisis

- Identificar columnas con tipos incorrectos, distribución y nulos, anotar las columnas que requieren conversión.
- Estandarizar los nombres de columnas para evitar errores y facilitar la unión de los datasets, y filtrar datos por el año relevante.
- Obtener una vista consolidada del tráfico promedio por ciudad y año, para analizar patrones generales sin depender de datos diarios.
- Combinar la información de tráfico y economía en un solo DataFrame para analizar cómo las condiciones económicas se relacionan con la movilidad urbana.
- Analizar visualmente la distribución y la relación entre indicadores de tráfico y economía en 2024 y generar insights para establecer correlación entre ambos.
