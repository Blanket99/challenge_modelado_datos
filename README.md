# Análisis de Ventas y Rendimiento de Tiendas

Este proyecto analiza datos de ventas de cuatro tiendas, integrando múltiples variables para evaluar su desempeño y apoyar la toma de decisiones comerciales. Se realiza un análisis descriptivo y visual con Python (Pandas, Matplotlib, Seaborn, Folium) para responder a preguntas clave sobre ingresos, productos, categorías, calificaciones y costos de envío.

---

## Contenido del Proyecto

- **Datos**: Archivos CSV individuales para cada tienda, con información de ventas, productos, precios, categorías, calificaciones, costos de envío y ubicación geográfica (latitud y longitud).
- **Código**: Python para cargar, limpiar, combinar, analizar y visualizar los datos.
- **Análisis**:
  - Ingresos totales por tienda.
  - Categorías de productos más vendidas.
  - Calificación promedio de clientes por tienda.
  - Productos más y menos vendidos.
  - Costo promedio de envío por tienda.
- **Visualizaciones**: Gráficos de barras y gráficos de dispersión.
- **Informe final**: Síntesis de hallazgos y recomendación estratégica.

---

## Estructura del Código

### 1. Carga y unificación de datos

- Se cargan los CSV de cada tienda.
- Se añade una columna `Tienda` para identificar la fuente.
- Se concatenan todos en un DataFrame unificado `df_unificado`.

### 2. Análisis descriptivo

- Se calculan ingresos totales por tienda.
- Se determina la categoría de producto más vendida por tienda.
- Se calcula la calificación promedio de clientes por tienda.
- Se identifican los productos más y menos vendidos en cada tienda.
- Se calcula el costo promedio de envío por tienda.

### 3. Visualización

- Se generan gráficos para cada análisis (barras para ingresos, categorías y productos; dispersión y mapas para análisis geográfico).
- Se usan librerías `matplotlib` y `seaborn` para la representación visual.

---

## Ejemplo de resultados obtenidos

- **Ingresos totales:** La Tienda 1 lidera con ingresos de ~1150 millones.
- **Categorías más vendidas:** En todas las tiendas, la categoría “Muebles” domina.
- **Calificación promedio:** Tienda 3 tiene la mejor valoración con 4.05/5⭐.
- **Productos más vendidos:** Varían por tienda, por ejemplo “Armario” en Tienda 1.
- **Productos menos vendidos:** También varían, como “Auriculares con micrófono” en Tienda 1.
- **Costos de envío:** Tienda 4 tiene el costo promedio más bajo.

---

## Recomendación final

Basado en los datos y análisis, se recomienda que el Sr. Juan enfoque sus esfuerzos de venta en las tiendas con mejor combinación de ingresos, satisfacción de clientes y ventas, especialmente Tienda 1 y Tienda 3, mientras se evalúa la viabilidad de optimizar o reestructurar la Tienda 4, que presenta menores ingresos y menor concentración geográfica.

---

## Cómo ejecutar el código

1. Clonar este repositorio o copiar el código en un Jupyter Notebook / Google Colab.
2. Asegurar conexión a internet para descargar los archivos CSV.
3. Ejecutar las celdas en orden para cargar datos, procesarlos, generar análisis y visualizaciones.
4. Explorar los gráficos y revisar el informe final.

---

## Librerías utilizadas

- pandas
- matplotlib
- seaborn
