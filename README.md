# 🛒 Análisis de ventas y comportamiento comercial de un eCommerce

## 📌 Descripción

Este proyecto analiza las transacciones de un eCommerce con el objetivo de
identificar los productos, mercados y periodos que generan mayores ingresos,
así como detectar patrones de compra, cancelaciones y oportunidades de mejora
comercial.

El análisis parte de más de **540 mil registros transaccionales** y abarca
desde la exploración y limpieza de los datos hasta la generación de
recomendaciones de negocio.

## 🎯 Objetivo

Responder la siguiente pregunta de negocio:

**¿Qué productos, mercados y periodos impulsan los ingresos del eCommerce y qué
oportunidades existen para mejorar su desempeño comercial?**

## 🛠️ Herramientas

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab
- GitHub

## 🔎 Metodología

El proyecto se desarrolló en las siguientes etapas:

1. Exploración inicial y evaluación de calidad de los datos.
2. Identificación y eliminación de registros duplicados.
3. Análisis de valores faltantes y transacciones atípicas.
4. Separación de ventas válidas, cancelaciones y otros movimientos.
5. Cálculo de KPIs comerciales.
6. Análisis de la evolución mensual de los ingresos.
7. Identificación de productos con mayor contribución.
8. Análisis de mercados y ticket promedio por país.
9. Evaluación de cancelaciones y operaciones revertidas.
10. Elaboración de conclusiones y recomendaciones de negocio.

## 📊 Principales KPIs

- **Ingresos de ventas válidas:** £10.64 millones
- **Pedidos de venta:** 19,960
- **Unidades vendidas:** 5.57 millones
- **Clientes identificados:** 4,338
- **Ticket promedio por pedido:** £533.17

## 💡 Principales hallazgos

### 1. Crecimiento hacia el cierre de 2011

Noviembre fue el mes completo con mayores ingresos, con aproximadamente
**£1.50 millones**. Los ingresos aumentaron **118% entre enero y noviembre**.

### 2. Productos con mayor contribución

`REGENCY CAKESTAND 3 TIER` fue el producto comercial con mayores ingresos.
El análisis también mostró que vender más unidades no necesariamente implica
generar mayores ingresos.

### 3. Alta concentración en Reino Unido

El **84.6% de los ingresos** provino del Reino Unido.

Entre los mercados internacionales destacaron Netherlands, EIRE, Germany y
France. Netherlands y Australia presentaron además tickets promedio elevados.

### 4. Cancelaciones relevantes

Se identificaron **3,836 facturas canceladas**, equivalentes a una tasa del
**16.12%**.

El valor bruto registrado en estas operaciones fue de aproximadamente
**£893,980**, aunque incluye tanto cancelaciones de productos como cargos y
ajustes administrativos.

## 💼 Recomendaciones de negocio

- Reforzar inventario y capacidad operativa en los periodos de mayor demanda.
- Priorizar productos considerando ingresos, volumen y frecuencia de compra.
- Analizar oportunidades de crecimiento en mercados internacionales con tickets
  promedio elevados.
- Reducir la dependencia del mercado británico mediante estrategias de
  diversificación.
- Separar devoluciones comerciales de ajustes administrativos para mejorar el
  seguimiento de cancelaciones.
- Incorporar más años de información, costos y márgenes para evaluar
  estacionalidad y rentabilidad.

## 📁 Archivos del repositorio

- `Análisis de ventas de comercio electrónico.ipynb` — Notebook con el análisis
  completo, código, visualizaciones, hallazgos y conclusiones.

## 👩‍💻 Autora

**Lidia Pineda**  
Proyecto de portafolio — Análisis de Datos
