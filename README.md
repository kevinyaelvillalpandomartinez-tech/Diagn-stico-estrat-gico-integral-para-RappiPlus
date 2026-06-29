# Diagnostico-estrategico-integral-para-RappiPlus
# 📊 RappiPlus Analytics: De Datos a Decisiones de Negocio

## 📌 Descripción del Proyecto

Este proyecto simula el trabajo de un **Data Analyst** dentro de una empresa de delivery llamada **RappiPlus**.

El objetivo es transformar datos provenientes de distintas áreas del negocio (ventas, marketing, comportamiento de usuarios y experimentos A/B) en información accionable que permita mejorar la rentabilidad, optimizar el embudo de conversión y aumentar la retención de clientes.

Durante el proyecto se aplican técnicas de:

- Limpieza y calidad de datos
- Análisis exploratorio (EDA)
- Cálculo de KPIs de negocio
- SQL para análisis de comportamiento
- Cohortes de retención
- Pruebas estadísticas A/B
- Storytelling con dashboards

---

# 🎯 Objetivos del Proyecto

Este análisis busca responder preguntas de negocio como:

- ¿El negocio es rentable?
- ¿Qué productos generan mayor utilidad?
- ¿En qué parte del proceso abandonan los usuarios?
- ¿Los clientes regresan después de registrarse?
- ¿La nueva interfaz del checkout realmente mejora la conversión?
- ¿Qué información debe visualizar la dirección para tomar mejores decisiones?

---

# 🛠 Tecnologías Utilizadas

| Herramienta | Uso |
|------------|-----|
| Python | Limpieza y análisis de datos |
| Pandas | Manipulación de datos |
| NumPy | Cálculos numéricos |
| Matplotlib | Visualizaciones |
| SQL | Análisis del comportamiento de usuarios |
| Power BI / Tableau | Dashboard Ejecutivo |
| Jupyter Notebook | Desarrollo del proyecto |

---

# 📂 Estructura del Proyecto

```
RappiPlus-Analytics
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── Kevin.ipynb
│
├── dashboards/
│
├── images/
│
├── documentation/
│
├── README.md
│
└── requirements.txt
```

---

# 📊 Dataset

El proyecto utiliza diferentes fuentes de información que representan áreas clave del negocio.

### Orders

Información de cada pedido realizado.

Incluye variables como:

- fecha
- producto
- cantidad
- precio
- revenue
- costo
- profit

---

### Catálogo

Contiene información del producto.

- categoría
- proveedor
- costo unitario

---

### Marketing

Información sobre inversión publicitaria.

- canal
- país
- gasto

---

### Eventos

Registro del comportamiento del usuario dentro de la aplicación.

Ejemplos:

- Home
- Search
- Product
- Cart
- Checkout
- Purchase

---

### Usuarios

Información utilizada para calcular la retención.

---

### Experimento A/B

Dos variantes del checkout.

- Control
- Tratamiento

Se utiliza para determinar si la nueva interfaz incrementa la conversión.

---

# 📈 Desarrollo del Proyecto

## 1️⃣ Calidad de Datos

Antes de realizar cualquier análisis se verificó la calidad de la información.

Se realizaron tareas como:

- Conversión de fechas
- Revisión de valores nulos
- Eliminación de duplicados
- Corrección de valores negativos
- Validación de montos
- Estandarización de variables categóricas

**Objetivo**

Garantizar que el análisis posterior estuviera basado en información confiable.

---

## 2️⃣ Análisis de Rentabilidad

Se calcularon los principales indicadores financieros del negocio.

Entre ellos:

- Revenue Total
- Costos Totales
- Profit
- Margen
- Ticket Promedio
- Productos más vendidos
- Categorías más rentables

Este análisis permitió identificar qué áreas generan mayor valor para la empresa.

---

## 3️⃣ Funnel de Conversión

Mediante SQL se analizó el recorrido de los usuarios dentro de la aplicación.

Se calcularon conversiones entre etapas como:

```
Home
 ↓
Search
 ↓
Product
 ↓
Cart
 ↓
Checkout
 ↓
Purchase
```

Con ello fue posible detectar los puntos donde el negocio pierde más usuarios.

---

## 4️⃣ Retención por Cohortes

Se construyó un análisis de cohortes para medir el comportamiento de los clientes a lo largo del tiempo.

Se identificó:

- usuarios recurrentes
- tasa de retención
- semanas con mayor abandono
- comportamiento por cohorte

Este análisis ayuda a comprender la fidelización de clientes.

---

## 5️⃣ Prueba A/B

Se evaluó estadísticamente una nueva versión del proceso de Checkout.

Se compararon:

- Grupo Control
- Grupo Tratamiento

Aplicando una prueba de diferencia de proporciones se determinó si la nueva interfaz mejoró significativamente la conversión.

El objetivo fue tomar una decisión basada en evidencia estadística y no únicamente en diferencias observadas.

---

## 6️⃣ Dashboard Ejecutivo

Finalmente se diseñó un dashboard para comunicar los hallazgos más importantes.

Incluye indicadores como:

- Revenue
- Profit
- Costos
- Marketing
- Funnel
- Conversión
- Retención
- KPIs principales

El dashboard está orientado a facilitar la toma de decisiones de negocio.
<img width="1311" height="743" alt="image" src="https://github.com/user-attachments/assets/51819fa9-9131-416b-b7cc-a3544ffcee25" />




---

# 📊 Principales Habilidades Demostradas

Durante este proyecto se aplicaron conocimientos en:

✅ Limpieza de datos

✅ Exploratory Data Analysis (EDA)

✅ KPIs de negocio

✅ SQL

✅ Python

✅ Estadística

✅ Pruebas A/B

✅ Funnel de Conversión

✅ Cohortes

✅ Storytelling con Datos

✅ Visualización en Power BI

---

# 💡 Principales Aprendizajes

Este proyecto permitió integrar diferentes disciplinas del análisis de datos para resolver problemas reales de negocio.

Entre los principales aprendizajes destacan:

- Importancia de la calidad de datos.
- Uso de KPIs para evaluar rentabilidad.
- Construcción de embudos de conversión.
- Medición de retención mediante cohortes.
- Validación estadística mediante experimentos A/B.
- Comunicación efectiva mediante dashboards.

---

# 🚀 Cómo ejecutar el proyecto

## 1. Clonar el repositorio

```bash
git clone https://github.com/TU-USUARIO/RappiPlus-Analytics.git
```

## 2. Entrar al proyecto

```bash
cd RappiPlus-Analytics
```

## 3. Instalar dependencias

```bash
pip install -r requirements.txt
```

## 4. Ejecutar Jupyter Notebook

```bash
jupyter notebook
```

Abrir:

```
Kevin.ipynb
```

---

# 👨‍💻 Autor

## Kevin Yael Villalpando Martínez

**Junior Data Analyst**

### Tecnologías

- Python
- SQL
- Power BI
- Excel
- Git
- GitHub

🌐 **Portafolio**

https://kevinyaelvillalpandomartinez-tech.github.io/kevinvillalpando.github.io/

💼 **LinkedIn**

https://www.linkedin.com/in/kevin-yael-villalpando-martinez-518272405/

---

# ⭐ Si este proyecto te resultó interesante...

No olvides dejar una ⭐ al repositorio.
