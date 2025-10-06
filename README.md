# 🛒 Online Retail Data Analysis

Este proyecto analiza un conjunto de datos de transacciones reales de un comercio electrónico, con el objetivo de explorar el comportamiento de los clientes, identificar patrones de compra y realizar una segmentación de clientes basada en métricas RFM (Recency, Frequency, Monetary).

---

## 📊 Dataset

El dataset **Online Retail** contiene más de 540,000 transacciones entre 2010 y 2011, registradas por una empresa de venta al por menor en línea con sede en el Reino Unido.  
Cada registro incluye información sobre:
- Número de factura (`InvoiceNo`)
- Producto (`Description`, `StockCode`)
- Cantidad (`Quantity`)
- Fecha de compra (`InvoiceDate`)
- Precio unitario (`UnitPrice`)
- Cliente (`CustomerID`)
- País (`Country`)

---

## Proceso del análisis

1. **Carga y limpieza de datos**
   - Eliminación de valores nulos (`CustomerID`, `Description`).
   - Conversión de fechas y cálculo del precio total por compra.
   - Filtrado de devoluciones (cantidades negativas).

2. **Análisis exploratorio (EDA)**
   - Identificación de los países y productos más rentables.
   - Visualización de patrones de compra con `matplotlib` y `seaborn`.

3. **Segmentación de clientes**
   - Cálculo de métricas RFM (Recency, Frequency, Monetary).
   - Agrupamiento de clientes mediante *K-Means Clustering*.
   - Análisis de los distintos segmentos y su valor para el negocio.

4. **Visualización**
   - Gráficos de dispersión y distribuciones.
   - Insights sobre comportamiento del cliente.

---

## 💻 Tecnologías utilizadas

- **Python 3.10+**
- **Pandas** para manipulación de datos.
- **Matplotlib** y **Seaborn** para visualización.
- **Scikit-learn** para segmentación (K-Means).
- **Jupyter Notebook** para documentación interactiva.

---
