# 📊 Proyecto Final – Análisis de Compras (Power BI)

📸  
![Página Compras](https://github.com/FranciscoIrago/assets/blob/main/adventure/adventure_portada.png)


Este proyecto consiste en el desarrollo de un **dashboard interactivo en Power BI Desktop** enfocado en el **análisis de compras de la empresa AdventureWorks**.  
El objetivo es ofrecer una visión global y dinámica del rendimiento de las compras, proveedores, empleados y productos, integrando distintos niveles de análisis mediante navegación entre páginas.

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
![Página Compras](https://github.com/FranciscoIrago/assets/blob/main/adventure/adventure_compras.png)

---

El dashboard principal **“Compras”** actúa como punto de partida e incluye dos botones interactivos:

- 🔹 **Ir al detalle** → lleva a la página **“Detalles Compras”**, centrada en el análisis tabular por proveedor y producto.  
- 🔹 **Ir al gráfico** → lleva a la página **“Gráficos Compras”**, donde se muestran visualizaciones comparativas y tendencias.

De este modo, el usuario puede explorar la información tanto desde un punto de vista **resumen (KPI)** como **analítico (detalle y gráficos)**.


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
![Detalles Compras](https://github.com/FranciscoIrago/assets/blob/main/adventure/adventure_detalle.png)

---

## 📊 **3. Gráficos Compras**

Página accesible desde el botón **“Ir al gráfico”**, centrada en la visualización dinámica.

Incluye:
- Gráficos comparativos entre **productos**, **categorías** y **empleados**.  
- Evolución mensual de las compras (Total vs. LY).  
- Distribución del gasto por proveedor.  
- Ranking de productos más comprados (HL Crankarm, ML Mountain Pedal, ML Road Pedal, etc.).

📸  
![Gráficos Compras](https://github.com/FranciscoIrago/assets/blob/main/adventure/adventure_graf.png)

---

## 👥 **4. Empleados**

Analiza las compras realizadas por cada empleado (Buyer), destacando:
- Total de compras por persona.  
- Productos más comprados por empleado.  
- Evolución mensual del gasto individual.

Este análisis permite identificar a los **empleados con mayor volumen de gestión de compras** y su contribución total.

📸  
![Empleados](https://github.com/FranciscoIrago/assets/blob/main/adventure/adventure_empleados.png)

---

## 🏢 **5. Proveedores**

Sección dedicada al rendimiento de los proveedores:
- **Distribución de las compras por proveedor.**  
- **Productos suministrados y su importe total.**  
- Comparación de proveedores clave (Superior Bicycles, Professional Athletic Consultants, Chicago City Saddles, etc.).  
- Evolución mensual de las compras por proveedor.

📸  
![Proveedores](https://github.com/FranciscoIrago/assets/blob/main/adventure/adventure_proveedores.png)

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

# 🏋️‍♂️ Proyecto Personal Trainer – Seguimiento de Entrenamiento y Nutrición (Power BI)

![Portada](https://github.com/FranciscoIrago/assets/blob/main/trainer/Protada.png)

Este proyecto consiste en el desarrollo de un **dashboard interactivo en Power BI Desktop** diseñado para realizar el **seguimiento del progreso físico, la rutina de entrenamiento y la dieta personal**.  
El objetivo es visualizar de manera integrada los avances en fuerza, peso corporal, pasos diarios, calorías quemadas y consumo calórico, permitiendo analizar la evolución tanto en el ámbito deportivo como nutricional.

---

## 🧭 Navegación del Informe

El informe está compuesto por tres secciones principales, accesibles desde el panel superior del dashboard:

- 💪 **Rutina:** seguimiento de entrenamiento, fuerza y volumen de trabajo.  
- 🍽️ **Dieta:** análisis nutricional diario y semanal.  
- 📈 **Evolución:** resumen general del progreso físico y calórico.

---

## 💪 **1. Rutina**

Esta página permite analizar la planificación y ejecución del entrenamiento.  
Incluye indicadores generales y visualizaciones por ejercicio y grupo muscular.

### 🔹 Principales indicadores:
- **Nombre del usuario:** Francisco Irago Lechuga  
- **Peso inicial:** 100 kg  
- **Peso final:** 80 kg  
- **Tipo de entrenamiento:** Fuerza  
- **Duración:** desde el 01/01/2025  
- **Frecuencia:** 4 días por semana  

### 📊 Métricas destacadas:
- Evolución del peso levantado en **Press Banca** (de 80 a 100 kg)  
- **Pasos totales:** 254.000  
- **Calorías quemadas:** 35.000  

📸  
![Rutina](https://github.com/FranciscoIrago/assets/blob/main/trainer/rutina.png)

---

## 🍽️ **2. Dieta**

Muestra la composición nutricional diaria y semanal, con desgloses por comida (desayuno, comida, merienda, cena).  
Permite analizar el equilibrio entre calorías ingeridas y calorías quemadas, así como la distribución de macronutrientes.

### 🔹 Principales indicadores:
- **Calorías totales ingeridas:** 7.821 kcal  
- **Calorías quemadas:** 26.240 kcal  
- **Déficit calórico acumulado:** 18.420 kcal  
- **Peso perdido:** 2,63 kg  

### 📋 Estructura del análisis:
- Comparativa de calorías, carbohidratos, proteínas, grasas y fibra por comida.  
- Control de días y horarios de ingesta.  
- Seguimiento semanal del balance calórico.

📸  
![Dieta](https://github.com/FranciscoIrago/assets/blob/main/trainer/dieta.png)

---

## 📈 **3. Evolución**

Página resumen del progreso físico general, combinando la información de la rutina y la dieta.

### 🔹 Indicadores principales:
- **Evolución del peso corporal.**  
- **Progreso de fuerza (por ejercicio).**  
- **Balance energético:** comparación entre calorías ingeridas y quemadas.  
- **Pasos diarios promedio y actividad física general.**

Incluye gráficos temporales que reflejan la tendencia de mejora y el déficit calórico acumulado, ofreciendo una visión global de la evolución durante el periodo de entrenamiento.

📸  
![Evolución](https://github.com/FranciscoIrago/assets/blob/main/trainer/ejercicio.png)

---

## 🧠 **Objetivos del Proyecto**
- Crear una herramienta visual que permita **controlar el progreso físico y nutricional** de forma sencilla e intuitiva.  
- Centralizar los datos de **entrenamiento, dieta y evolución corporal** en un único panel.  
- Facilitar la **toma de decisiones deportivas** (ajustes de dieta, peso de trabajo, frecuencia de entrenamiento).  
- Motivar al usuario mediante el seguimiento del rendimiento y la evolución real de resultados.

---

##

# Dashboard de Estadísticas de Fútbol ⚽

## Descripción del Proyecto

![Portada](https://github.com/FranciscoIrago/assets/blob/main/futbol/1Portada.png)

[cite_start]Este proyecto presenta un dashboard interactivo enfocado en el análisis detallado de estadísticas de **Fútbol** (FOOTBAL)[cite: 6]. El objetivo es proporcionar una visualización clara y profunda del rendimiento de equipos y jugadores a lo largo de varias temporadas y competiciones. [cite_start]El dashboard incluye secciones para Equipos [cite: 3][cite_start], Ligas [cite: 4] [cite_start]y Jugadores[cite: 5].

## Características Principales

El dashboard se compone de varias secciones clave, diseñadas para ofrecer una perspectiva completa de las métricas deportivas:

### 1. Vista General del Equipo

* [cite_start]**Resumen de Puntos y Goles:** Muestra los puntos acumulados (e.g., 322 (44,72%) [cite: 14, 15] [cite_start]y 398 (55,28%) [cite: 28][cite_start]) y los goles totales [cite: 35, 40][cite_start], con una distribución de Goles (e.g., Global [cite: 31][cite_start], Local [cite: 32, 36][cite_start], Visitante [cite: 33]).
* [cite_start]**Análisis Histórico por Temporada:** Una tabla detallada que compara el rendimiento a lo largo de múltiples temporadas (e.g., 2008/2009 hasta 2015/2016)[cite: 37].
    * [cite_start]**Métricas incluidas:** Temporada [cite: 37][cite_start], Puntos [cite: 24, 30, 37][cite_start], Victorias [cite: 37][cite_start], Empates [cite: 37][cite_start], Derrotas [cite: 37][cite_start], Goles Marcados (GMarc) [cite: 37][cite_start], Goles Recibidos (GReci) [cite: 37] [cite_start]y Diferencia de Goles (GDiff)[cite: 37].
    * [cite_start]**Temporada con más puntos:** Se destaca la 2011/2012 con 100 puntos[cite: 29, 30].
* [cite_start]**Contexto de la Competición:** La Liga mostrada es "Spain LIGA BBVA" [cite: 18, 129] [cite_start]y el Equipo es "Real Madrid CF" (parcialmente visible)[cite: 20].

![Equipos](https://github.com/FranciscoIrago/assets/blob/main/futbol/2Equipos.png)

### 2. Rendimiento Individual de Jugadores

* [cite_start]**Perfil de Cristiano Ronaldo:** Muestra una ficha de rendimiento detallada para el jugador [cite: 61, 66][cite_start], para la Temporada **2011/2012** [cite: 64, 76] [cite_start]y la liga **Spain LIGA BBVA**[cite: 62, 63].
* **Métricas Clave:**
    * [cite_start]Estadísticas de **Goles (46)** [cite: 65] [cite_start]y **Penaltys (12)**[cite: 83, 84].
    * [cite_start]**Overall:** 91,28[cite: 87, 88].
    * [cite_start]**Atributos de Habilidad:** Presentados en un gráfico de radar y desglosados con puntuaciones numéricas: Velocidad (93,76) [cite: 89][cite_start], Salto (93,04) [cite: 90, 91][cite_start], Potencia de Disparo (92,76) [cite: 92][cite_start], Regate (92,64) [cite: 93, 94][cite_start], Aceleración (91,64) [cite: 96][cite_start], Definición (91,12) [cite: 97][cite_start], Tiro Lejano (89,88) [cite: 99, 103][cite_start], Remate de Cabeza (85,52) [cite: 100, 104][cite_start], Penalties (83,60) [cite: 109, 111][cite_start], Pase Corto (82,28) [cite: 110, 112][cite_start], Faltas (81,64) [cite: 114, 115][cite_start], y Pase Largo (71,72)[cite: 113].

![Jugadores](https://github.com/FranciscoIrago/assets/blob/main/futbol/3Jugadores.png)

### 3. Análisis de Factores de Éxito

* [cite_start]**Elementos Influyentes Clave:** Identifica los "Elementos influyentes clave" y "Segmentos principales" [cite: 117] [cite_start]que impactan en el "Nivel Victorias"[cite: 118].
* **Análisis Condicional (Probabilidad de Victoria Alta):**
    * [cite_start]Cuando `defence Team Width` sube, la probabilidad se incrementa 2.57x (con un valor de 10.33)[cite: 120, 121, 127].
    * [cite_start]Cuando `buildUpPlaySpeed` sube (13.11), el incremento es 2.28x[cite: 131, 132, 133].
    * [cite_start]Cuando `chanceCreationPositioning...` es Free Form, el incremento es 2.10x[cite: 136, 137, 138].
    * [cite_start]Se observa que cuando `defence Team Width` aumenta, la probabilidad de que Nivel Victorias sea Alta también lo hace[cite: 144].

![Stats](https://github.com/FranciscoIrago/assets/blob/main/futbol/4Stats.png)

## Tecnologías Utilizadas

* [Lista las tecnologías que has usado, por ejemplo: Python, Pandas, Matplotlib/Seaborn, Dash/Plotly, React, etc.]

## Instalación y Uso

[Instrucciones claras sobre cómo clonar el repositorio, instalar dependencias y ejecutar el dashboard localmente.]

## Contribuciones

[Información sobre cómo otros pueden contribuir al proyecto.]
