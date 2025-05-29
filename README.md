## 🛒 Análisis de comportamiento de compra en Instacart

### 📌 Introducción

Este proyecto analiza datos transaccionales de Instacart, una plataforma de entregas de comestibles similar a Uber Eats o DoorDash. El objetivo principal es realizar un análisis exploratorio de datos y detectar patrones en el comportamiento de los consumidores. Para ello, se trabaja con cinco tablas interrelacionadas y se realiza una limpieza exhaustiva de valores duplicados y ausentes antes de proceder al análisis.

### Objetivo

Preparar y explorar un conjunto de datos multi-tabla para detectar relaciones entre productos, departamentos y hábitos de compra, con el fin de obtener insights accionables sobre el comportamiento de los clientes.

---

### 🧠 Habilidades técnicas demostradas

Este proyecto demuestra competencias clave en ciencia de datos, particularmente en el manejo de datos tabulares y su depuración para generar posteriormente visualizaciones clave para el negocio. Entre las habilidades aplicadas se encuentran:

- **Limpieza de datos**: detección y tratamiento de valores nulos y duplicados en múltiples DataFrames.
- **Reformateo de datos**: corrección de tipos de datos (`object` a `int`/`float`) para permitir su análisis posterior.
- **Análisis exploratorio de datos (EDA)**: comprensión de relaciones entre categorías, como departamentos y tipos de productos.
- **Agrupación y segmentación de datos**: uso de `groupby()` para obtener patrones agregados.
- **Lectura y fusión de múltiples fuentes**: integración de varios conjuntos de datos para construir una vista unificada del cliente.
- **Visualización de datos**: generación de gráficos con `matplotlib` y el método `.plot()` para representar tendencias clave.
- **Documentación estructurada**: claridad en la descripción del flujo de trabajo para facilitar la lectura técnica.

---

### 🛠️ Tecnologías y herramientas utilizadas

- **Python**: lenguaje principal para el análisis.
- **pandas**: para manipulación de datos tabulares.
- **matplotlib**: para visualización de datos.
- **Funciones clave**: `.groupby()`, `.merge()`, `.isnull()`, `.drop_duplicates()`, `.astype()`, `.plot()`

---

### ✅ Resultados y conclusiones

- Se logró preparar de forma eficiente cinco tablas con estructuras distintas y múltiples relaciones.
- Se eliminaron duplicados y valores ausentes, permitiendo una visión limpia del flujo de compra del cliente.
- El análisis identificó patrones clave como:
  - Productos más comprados.
  - Frecuencia de pedidos por usuario.
  - Relación entre departamentos y categorías de productos.
  - Comportamientos y patrones de compra de los usuarios a través del tiempo.

---

### 📈 Posibles mejoras futuras

- Construir un dashboard interactivo con `Streamlit` o `Power BI`.
- Implementar modelos de predicción de compra utilizando `scikit-learn`.

---

### 👨‍💻 Autor

**Andrés Calvete**  
Científico de Datos Junior  
[LinkedIn](https://www.linkedin.com/in/andrescalvete/)  
ascalvete@hotmail.com
