# Actividad 2 — Detección de atípicos y operaciones groupby()

**Maestría en Ciencia de Datos — Yachay Tech**

**Asignatura:** Fundamentos de Inteligencia Artificial

## Objetivo

Analizar transacciones de comercio electrónico utilizando Python,
pandas, técnicas de limpieza de datos, detección de valores atípicos
mediante IQR y operaciones de agrupamiento con groupby().

## Dataset

- Registros originales: 536.350
- Registros después de eliminar nulos: 535.056
- Registros finales después de los filtros: 470.329

## Metodología

1. Carga y exploración de las transacciones.
2. Identificación y eliminación de valores nulos.
3. Detección de valores atípicos mediante IQR.
4. Cálculo de ingresos por producto.
5. Agrupamiento con pandas groupby().
6. Visualización de productos, ingresos y tendencias temporales.

## Resultados principales

- Producto más vendido: Jumbo Bag Red Retrospot (14.050 unidades).
- Producto con mayores ingresos: Regency Cakestand 3 Tier.
- Mes con mayores ingresos agrupados: noviembre.
- Día con más líneas de transacción: viernes.

## Limitaciones

Los resultados corresponden a los registros filtrados.
El análisis mensual combina los mismos meses de años diferentes.
El conteo semanal representa líneas de transacción, no facturas únicas.

## Tecnologías

Python, pandas, NumPy, Matplotlib, Seaborn y Jupyter Notebook.

## Ejecución

Abrir el archivo .ipynb en VS Code, seleccionar un kernel
de Python y ejecutar las celdas en orden.
El CSV debe permanecer en el mismo directorio que el notebook.
