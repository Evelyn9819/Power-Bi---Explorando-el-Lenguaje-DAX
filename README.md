# 🧠 Power BI - Explorando el Lenguaje DAX

Este proyecto forma parte de una clase práctica centrada en **el uso de DAX (Data Analysis Expressions)** dentro de Power BI. El objetivo fue ir más allá de los cálculos simples y aplicar medidas personalizadas que permitan obtener insights más complejos a partir de datos de ventas de consolas de videojuegos.

> “Sin DAX, Power BI es solo una cara bonita; DAX es el motor detrás de los hallazgos significativos.”  
> — Marco Russo

---

## 📌 Objetivo del proyecto

Demostrar cómo el uso de DAX potencia los análisis en Power BI mediante la creación de medidas dinámicas que responden a contextos de filtro, tiempo y condiciones específicas del negocio.

---

## 🛠️ Herramientas utilizadas

- **Power BI Desktop**
- **Lenguaje DAX**
- **Modelo estrella** (Tablas: `Venta`, `Productos`, `Cuota`, `Calendario`)

---

## 📊 Métricas desarrolladas 

Se desarrollaron y aplicaron las siguientes medidas DAX:

1. **Unidades Vendidas**  
2. **Venta en Dólares (SUM y SUMX)**  
3. **Cuota Total y Alcance de Cuota (%)**  
4. **Ventas por Marca (Nintendo)**  
5. **Ventas por Región/Canal (No Online - Asia)**  
6. **Análisis MTD y YTD**  
7. **Comparativo Año Pasado (YTD y diferencia %)**  
8. **Análisis por Producto específico (Switch 2)**  
9. **Medida de Estado (BIEN / REVISAR)**  

Estas medidas permitieron crear visualizaciones con **análisis comparativos**, **tendencias temporales**, y **cumplimiento de metas** de forma clara y dinámica.

---

## 🗓️ Tabla de calendario personalizada

Se implementó una tabla de calendario personalizada utilizando DAX para habilitar el análisis de tiempo (`MTD`, `YTD`, `Año Anterior`), incluyendo columnas como:

- `Mes` (nombre y número)
- `Año`
- `Día`
- `Semana`

---

## 🖼️ Vista del dashboard final

![Dashboard Final](ruta/a/tu/imagen.png) <!-- Reemplaza con la ruta real del archivo o un link -->

---

## 🧠 Lecciones aprendidas

- Profundización en el uso de **CALCULATE** y funciones de tiempo como `TOTALYTD`, `DATEADD`.
- Aplicación de **columnas calculadas** y **variables**.
- Importancia del **contexto de evaluación** y el diseño de modelos semánticos robustos.

---

## 🚀 Próximos pasos

- Automatizar alertas de cumplimiento de cuota con formato condicional.
- Añadir segmentación por canales y tipo de consola con bookmarks.
