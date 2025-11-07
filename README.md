# Challenge-tiendas

# 🛒 Análisis de Ventas AluraStore Latam 📊

Este proyecto contiene un análisis exploratorio de los datos de ventas de cuatro tiendas de AluraStore en Latinoamérica (Tienda 1, Tienda 2, Tienda 3 y Tienda 4). El análisis se centra en métricas clave como facturación, rendimiento por categoría, calificación promedio y costos de envío.

---

## 🎯 Propósito del Análisis

El objetivo principal de este análisis es **evaluar el rendimiento comercial de cada una de las cuatro tiendas** de AluraStore de manera individual.

Los principales propósitos son:

* **Medir la Facturación:** Determinar el ingreso total generado por cada tienda.
* **Identificar Rendimiento:** Conocer las categorías de productos que generan mayores ingresos y los productos más vendidos en cada ubicación.
* **Evaluar la Satisfacción:** Calcular la calificación promedio de los clientes para monitorear la calidad del servicio.
* **Analizar Costos:** Determinar el costo de envío promedio por tienda.

---

## 📁 Estructura del Proyecto y Organización de Archivos

El proyecto está organizado en un único archivo de Jupyter Notebook que contiene todos los pasos de la importación, limpieza y análisis de los datos.

| Archivo/Carpeta | Descripción |
| :--- | :--- |
| `AluraStoreLatam.ipynb` | Contiene el código Python y los resultados del análisis. Lee los datos directamente de los repositorios de GitHub. |
| **`tienda_1.csv`** (URL) | Base de datos de ventas de la Tienda 1. |
| **`tienda_2.csv`** (URL) | Base de datos de ventas de la Tienda 2. |
| **`tienda_3.csv`** (URL) | Base de datos de ventas de la Tienda 3. |
| **`tienda_4.csv`** (URL) | Base de datos de ventas de la Tienda 4. |

---

## 📈 Ejemplos de Resultados e Insights Obtenidos

A continuación se muestran ejemplos de los principales resultados obtenidos en el análisis:

### 1. Facturación Total (Ejemplo)

| Tienda | Facturación Total |
| :--- | :--- |
| Tienda 1 | 806.273.600 |
| Tienda 2 | 827.848.300 |
| Tienda 3 | 741.523.100 |
| Tienda 4 | 774.209.700 |

> **💡 Insight de Facturación:** *La Tienda 2 es la que generó la mayor facturación total, mientras que la Tienda 3 tuvo el rendimiento más bajo.*

### 2. Producto Más Vendido (Ejemplo - Tienda 1)

El producto más vendido en la Tienda 1 por cantidad de transacciones fue la **"Silla de oficina"**.

### 3. Calificación Promedio (Ejemplo)

| Tienda | Calificación Promedio |
| :--- | :--- |
| Tienda 1 | 2.96 / 5.0 |
| Tienda 2 | 2.98 / 5.0 |
| Tienda 3 | 3.01 / 5.0 |
| Tienda 4 | 2.99 / 5.0 |

> **💡 Insight de Calificación:** *Todas las tiendas mantienen una calificación promedio muy similar, cercana a 3 sobre 5, lo que sugiere una oportunidad de mejora generalizada en la satisfacción del cliente.*

---

## 🚀 Instrucciones de Ejecución (Google Colab)

Sigue estos sencillos pasos para abrir y ejecutar el análisis:

1.  **Abrir el Notebook:** Sube el archivo `AluraStoreLatam.ipynb` a tu Google Drive o directamente a Google Colab.
2.  **Verificar Importación:** Asegúrate de que la primera celda de código, que importa las librerías (`pandas`) y carga los cuatro archivos CSV (`tienda`, `tienda2`, `tienda3`, `tienda4`), se haya ejecutado correctamente.
3.  **Ejecutar Celdas:** Ve ejecutando secuencialmente las celdas de código bajo cada uno de los títulos (`#1. Análisis de facturación`, `#2. Ventas por categoría`, etc.) para obtener los resultados de las cuatro tiendas.
4.  **Ver Resultados:** Los resultados aparecerán impresos justo debajo de cada bloque de código.
