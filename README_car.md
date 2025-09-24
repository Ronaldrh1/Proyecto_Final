#  Proyecto Final: Análisis de Ventas de Coches
Este proyecto tiene como objetivo aplicar técnicas de Análisis Exploratorio de Datos (EDA) y visualización mediante Power BI, basándose en un dataset de ventas de coches.

# Objetivo
- Realizar una limpieza y transformación profunda del dataset.
- Analizar estadísticas descriptivas relevantes.
- Visualizar insights mediante gráficos.
- Crear un dashboard interactivo en Power BI.

# Herramientas utilizadas
- Python (EDA y limpieza)
- Pandas
- Matplotlib
- Power BI (visualización y dashboard)
- Visual Studio Code

# 1. Preparación de datos
- Se cargó el dataset `car_sales_data.csv`.
- Se limpiaron columnas innecesarias y se estandarizaron nombres.
- Se convirtieron columnas numéricas (`Price`, `Mileage`) y categóricas (`Fuel Type`, `Manufacturer`).
- Se creó una columna nueva `Price_Range` para segmentar por rangos de precio.

# 2. Análisis descriptivo
- Total de modelos únicos disponibles.
- Precio promedio general y máximo.
- Combustible más frecuente en los vehículos.
- Modelos con mayor precio total acumulado.
- Relación entre kilometraje y precio.

# 3. Visualizaciones en Power BI
- Tarjetas KPI:
  - Total de modelos únicos
  - Precio promedio
  - Precio máximo
  - Combustible más usado
- Barras horizontales:
  - Precio total por modelo
  - Precio por fabricante
- Diagrama de dispersión:
  - Precio vs Kilometraje según tipo de combustible
- Gráfico de pastel:
  - Distribución de coches por tipo de combustible
- Tablas dinámicas con estadísticas agrupadas
- Segmentaciones:
  - Modelo, combustible, precio, y rango de precio

# Conclusiones
Este proyecto permitió explorar el comportamiento de ventas de coches en diferentes segmentos de precio, tipo de combustible y fabricante. El dashboard construido en Power BI facilita la toma de decisiones visualizando la información de forma clara y dinámica.