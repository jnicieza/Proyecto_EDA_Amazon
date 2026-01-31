# 📦📊 EDA de Ventas de Amazon (Datos Sintéticos)

## 📝 Descripción del Proyecto
Este proyecto realiza un **Análisis Exploratorio de Datos (EDA)** sobre un conjunto de datos **sintéticos de ventas de Amazon**, descargados desde **Kaggle**.  
El objetivo es comprender el comportamiento de las ventas, transformar los datos para obtener métricas clave y generar un **Dashboard** que permita visualizar los principales indicadores del negocio.

---

## 📁 Estructura del Proyecto
📦 Proyecto_EDA_Amazon
 ├── 📁 Data
 │     └── amazon_sales.csv
 ├── 📁 EDA
 │     └── amazon_sales_eda_dashboard.xlsx
 └── README.md

---

## 📊 Dataset
- **Fuente:** Kaggle (dataset sintético de ventas de Amazon).  https://www.kaggle.com/datasets/rohiteng/amazon-sales-dataset/data
- **Contenido:** información de pedidos, productos, clientes, fechas, países, métodos de pago, ingresos y devoluciones.  
- **Naturaleza:** datos sintéticos, por lo que pueden existir patrones o distribuciones no realistas.

---

## 🔍 Procesos Realizados

### 🧹 Limpieza y Transformación
- Revisión de la **consistencia de datos** identificando celdas en blanco
- Identificación de **clientes únicos**.  
- Cálculo de **ingresos netos** a partir de ingresos brutos y devoluciones.  
- Clasificación de fechas por **trimestres**.  
- Revisión de consistencia entre **ciudades y países**.  
- Preparación de datos para visualización en Dashboard.

---

### 📈 Exploración de Datos
- Análisis de ventas por:
  - País  
  - Método de pago  
  - Marca  
  - Categoría de producto  
- Estudio de tendencias temporales entre **2020 y 2024**.  
- Revisión de distribución de productos por marca.

---

## 🎯 KPIs Seleccionados
- 👥 **Clientes únicos**  
- 📦 **Productos pedidos**  
- 🚚 **Productos entregados**  
- 🔄 **Tasa de devolución**  
- 💰 **Ingresos brutos**  
- 💵 **Ingresos netos**

---

## 📊 Dashboard
El Dashboard incluido en la carpeta **EDA** contiene:

- Tarjetas con los **KPIs principales**.  
- Gráfica de **evolución de ventas e ingresos netos (2020–2024)**.  
- Ranking de **marcas más y menos vendidas**.  
- Volumen total por marca de ventas y devoluciones.  
- Distribución de ventas por **países**.  
- Distribución de ventas por **métodos de pago**.

---

## 🧠 Hallazgos Relevantes
- ❗ **Inconsistencias detectadas** entre ciudades y países, indicando errores en la referencia geográfica del dataset.  
- 🏷️ **Distribución anómala de productos por marca**: todas las marcas parecen ofrecer todos los tipos de productos, lo que refuerza el carácter sintético del dataset.  
- 🌍 Diferencias notables en ventas entre países.  
- 💳 Variabilidad en el uso de métodos de pago.  
- 📈 Tendencia de mantenimiento de ingresos netos a lo largo del periodo analizado. Otro signo que refuerza el carácter sintético de los datos.

---

## ⚙️ Requisitos
- Excel o equivalente para visualizar el Dashboard.  
- (Opcional) Python y librerías de análisis si se desea ampliar el EDA:
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  

---

## 🤝 Contribuciones
Las contribuciones son bienvenidas. Puedes abrir un *issue* o enviar un *pull request*.

---

## 📄 Licencia
Proyecto de uso libre con fines académicos.

## ✍️ Autor
- Javier Nicieza
- https://github.com/jnicieza
