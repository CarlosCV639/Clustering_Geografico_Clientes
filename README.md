# Clustering Geográfico de Clientes con Machine Learning (DBSCAN y KMeans)

Este proyecto aplica técnicas de machine learning no supervisado para agrupar geográficamente clientes de una empresa de energía. El objetivo es identificar agrupaciones de clientes (clusters) basadas en coordenadas geográficas y dividir los grandes clusters en subgrupos manejables, esto con la finalidad de generar estrategias de cobranza para los clusters más críticos.

<div align="center">
  <img width="750" alt="image" src="https://github.com/user-attachments/assets/8b2930a5-bd0c-4955-9a22-2ed7b75966d1" />
</div>


# Flujo de trabajo

- Carga y limpieza de datos desde un archivo CSV.
- Filtrado de registros según reglas del negocio.
- Clustering geográfico usando DBSCAN con distancia haversine.
- Subclustering de clusters grandes usando KMeans.
- Exportación del resultado final a un nuevo CSV.
- Visualizaciones:
  - Gráfico 2D estático con Matplotlib.
  - Mapa interactivo con Plotly.

# Análisis de los Clusters

Se genera un resumen estadístico por cluster que incluye:

- Total de clientes
- Deuda total
- Consumo kwh promedio
- Antigüedad de deuda promedio

Esto permite priorizar la atención a los clusters con mayor impacto económico.

# Conclusión

Gracias a la segmentación geográfica y al agrupamiento inteligente de clientes:

- Se optimizó la planificación de rutas para el personal de campo.
- Se identificaron agrupaciones críticas de clientes con alta deuda y antigüedad.
- Se logró priorizar la atención en zonas de mayor impacto económico.

## Resultados alcanzados:

- Aumento en los indicadores de recaudación mensual en zonas priorizadas.
- Mejora en la eficiencia operativa del contratista encargado de los cortes y reconexiones.
- Reducción del tiempo promedio de atención por cuadrilla.
