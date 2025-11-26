# 📊 Adidas U.S. Sales Analysis (2020-2021)

## 📝 Descripción del Proyecto
Este proyecto es un análisis de datos **"End-to-End"** diseñado para evaluar el rendimiento comercial de Adidas en Estados Unidos durante el período 2020-2021. El objetivo principal fue transformar datos crudos en información accionable para optimizar márgenes, gestión de inventario y estrategias de ventas.

## 🛠️ Herramientas y Tecnologías
* **Power BI:** Visualización y construcción del dashboard interactivo.
* **Power Query:** Procesamiento ETL (Extracción, Transformación y Carga) y limpieza de datos.
* **DAX (Data Analysis Expressions):** Creación de medidas complejas para KPIs (Márgenes operativos, comparativas temporales y ratios).
* **Modelado de Datos:** Diseño de esquema relacional (Star Schema) integrando tablas de Hechos (*Sales*) y Dimensiones (*Retailers, Products, Calendar*).

## 🔍 Metodología
1.  **Limpieza de Datos (ETL):** Normalización de tipos de datos y depuración de registros nulos utilizando Power Query.
2.  **Modelado:** Creación de relaciones "uno a muchos" para asegurar la integridad del análisis temporal y geográfico.
3.  **Cálculos:** Implementación de funciones DAX (`CALCULATE`, `DIVIDE`, `SUM`) para métricas de rentabilidad.
4.  **Visualización:** Desarrollo de un reporte de 4 páginas enfocado en Productos, Tendencias Espacio-Temporales y Métodos de Venta.

## 🚀 Insights Clave
* **Rentabilidad Digital:** Aunque las ventas en tienda física representan el **72.5%** del volumen total, el canal **Online** ofrece un margen de ganancia superior (**39%** vs 36%).
* **Producto Estrella:** "Men's Street Footwear" lidera tanto en ingresos brutos como en rentabilidad operativa.
* **Patrones Estacionales:** Se detectaron picos de venta críticos en el **Q3 (Julio-Septiembre)** y **Diciembre**, sugiriendo oportunidades para estrategias de stock específicas.
* **Liderazgo Regional:** La región **West** domina el mercado en volumen de ventas.

---
*Este proyecto fue realizado como parte de mi portfolio de Data Analytics.*
