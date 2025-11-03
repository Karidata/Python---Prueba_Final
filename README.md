# 📊 Análisis de Ventas con PostgreSQL y Jupyter

Este proyecto presenta una prueba técnica de análisis de datos aplicada sobre el dataset **ClassicModels**, utilizando **PostgreSQL como motor de base de datos** y **Jupyter Notebook como entorno de trabajo**. El objetivo es demostrar habilidades en integración de datos, cálculo de métricas comerciales, generación de reportes y aplicación de buenas prácticas como el principio **DRY**.

---

## 🚀 Objetivos del proyecto

- Importar y estructurar datos relacionales desde un archivo `.sql`
- Realizar cruces de tablas con integridad referencial
- Calcular métricas clave: **venta**, **costo** y **ganancia**
- Generar reportes agregados por línea de producto
- Identificar clientes activos e inactivos
- Filtrar y analizar ventas del año 2005
- Exportar reportes a PostgreSQL
- Aplicar el principio **DRY** mediante funciones reutilizables

---

## 🧠 Tecnologías utilizadas

- **PostgreSQL**: Motor de base de datos relacional
- **SQLAlchemy**: Conexión entre Python y PostgreSQL
- **Pandas**: Manipulación de datos tabulares
- **Jupyter Notebook**: Entorno interactivo para análisis y visualización
- **Python**: Lenguaje principal para lógica y funciones

---

## 📁 Estructura del repositorio

Estructura del repositorio:
├── README.md  
├── classicmodels.sql          # Archivo fuente con datos relacionales  
├── notebook.ipynb             # Desarrollo completo de la prueba  
├── funciones.py               # Funciones reutilizables para aplicar DRY


---

## 📊 Resultados clave

- ✅ Cruce de 4 tablas con validación de claves
- ✅ Cálculo de métricas por línea de detalle
- ✅ Reporte de ventas por línea de producto con fila TOTAL
- ✅ Identificación de clientes sin compras
- ✅ Top 10 clientes y productos del año 2005
- ✅ Exportación de reportes a PostgreSQL
- ✅ Funciones reutilizables para filtros, agrupaciones y exportación

---

## ✅ Conclusión

Este proyecto demuestra la capacidad de integrar datos relacionales, aplicar análisis comercial con Python y PostgreSQL, y estructurar soluciones reutilizables mediante buenas prácticas como el principio DRY. Una base sólida para proyectos de análisis de datos reales y escalables.
