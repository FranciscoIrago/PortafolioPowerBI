# 📊 Proyecto Final – Análisis de Compras (Power BI)

Este proyecto consiste en el desarrollo de un **dashboard interactivo en Power BI Desktop** enfocado en el **análisis de compras de la empresa AdventureWorks**.  
El objetivo es ofrecer una visión global y dinámica del rendimiento de las compras, proveedores, empleados y productos, integrando distintos niveles de análisis mediante navegación entre páginas.

---

## 🧭 Navegación del Informe

El dashboard principal **“Compras”** actúa como punto de partida e incluye dos botones interactivos:

- 🔹 **Ir al detalle** → lleva a la página **“Detalles Compras”**, centrada en el análisis tabular por proveedor y producto.  
- 🔹 **Ir al gráfico** → lleva a la página **“Gráficos Compras”**, donde se muestran visualizaciones comparativas y tendencias.

De este modo, el usuario puede explorar la información tanto desde un punto de vista **resumen (KPI)** como **analítico (detalle y gráficos)**.

---

## 🏠 **1. Compras (Página principal)**

Presenta los principales indicadores y filtros de análisis:

- 💰 **Importe total de compras:** 63,8 millones €  
- 📦 **Número total de compras:** 4.012  
- 🏆 **Proveedor más comprado:** Superior Bicycles  
- 🧾 **Producto más comprado:** HL Crankarm  
- 💶 **Precio medio:** 34,74 €  
- ⚠️ **Porcentaje de cantidad rechazada:** 3,10 %  
- 🚚 **Método de envío más utilizado:** Cargo Transport 5 (63,59 %)

Incluye además gráficos de:
- Evolución mensual de compras (comparativa año actual vs. año anterior)
- Compras por categoría y subcategoría
- Distribución de compras por proveedor

📸  
![Página Compras](https://github.com/FranciscoIrago/PortafolioPowerBI/blob/main/assets/adventure_compras.png)

---

## 📋 **2. Detalles Compras**

Página de análisis en profundidad, accesible desde el botón **“Ir al detalle”**.

Permite examinar:
- La relación entre proveedores, cantidades y precios.  
- Porcentaje de productos rechazados.  
- Totales de compras por proveedor y producto.  
- Identificación de **proveedores con mayor volumen de compras o incidencias**.  

Ejemplo de indicadores:
- **Precio medio general:** 34,74 €  
- **Precio máximo:** 82,83 €  
- **Proveedor más rechazado:** International

📸  
![Detalles Compras](imagenes/detalles_compras.png)

---

## 📊 **3. Gráficos Compras**

Página accesible desde el botón **“Ir al gráfico”**, centrada en la visualización dinámica.

Incluye:
- Gráficos comparativos entre **productos**, **categorías** y **empleados**.  
- Evolución mensual de las compras (Total vs. LY).  
- Distribución del gasto por proveedor.  
- Ranking de productos más comprados (HL Crankarm, ML Mountain Pedal, ML Road Pedal, etc.).

📸  
![Gráficos Compras](https://github.com/FranciscoIrago/PortafolioPowerBI/blob/main/assets/adventure_graf.png)

---

## 👥 **4. Empleados**

Analiza las compras realizadas por cada empleado (Buyer), destacando:
- Total de compras por persona.  
- Productos más comprados por empleado.  
- Evolución mensual del gasto individual.

Este análisis permite identificar a los **empleados con mayor volumen de gestión de compras** y su contribución total.

📸  
![Empleados](https://github.com/FranciscoIrago/PortafolioPowerBI/blob/main/assets/adventure_empleados.png)

---

## 🏢 **5. Proveedores**

Sección dedicada al rendimiento de los proveedores:
- **Distribución de las compras por proveedor.**  
- **Productos suministrados y su importe total.**  
- Comparación de proveedores clave (Superior Bicycles, Professional Athletic Consultants, Chicago City Saddles, etc.).  
- Evolución mensual de las compras por proveedor.

📸  
![Proveedores](https://github.com/FranciscoIrago/PortafolioPowerBI/blob/main/assets/adventure_proveedores.png)

---

## 🧠 **Objetivos del Proyecto**
- Ofrecer una **visión integral de las compras** y su evolución temporal.  
- Facilitar la **toma de decisiones** basada en indicadores de rendimiento.  
- Evaluar la **eficiencia de proveedores y empleados** en el proceso de compra.  
- Identificar oportunidades de mejora en los **costes y logística de envío**.

---

## 🛠️ **Herramientas Utilizadas**
- **Power BI Desktop**  
- **Microsoft SQL Server (AdventureWorks)**  
- **Modelado de datos y medidas DAX**  
- **Diseño de navegación con botones y filtros dinámicos**

---

## 👤 **Autor**
**Francisco Irago**  
Proyecto final desarrollado como parte de la formación en **análisis y visualización de datos con Power BI**.

---

### 🎥 **Vista Previa del Proyecto**
*(Puedes añadir aquí un enlace o imagen de tu dashboard si lo subes a GitHub o lo presentas en vídeo)*

[![Ver demo del proyecto](https://img.shields.io/badge/🎬%20Ver%20Demo-%23FF0000?style=for-the-badge)](ENLACE_A_TU_VIDEO_O_IMAGEN)
