# 📈 Proyecto Integrador: Visualización de Datos (Módulo 5)
### Diplomado en Fundamentos de Análisis de Datos — SENCE

---

## 📝 Descripción del Proyecto
Este proyecto representa la culminación del proceso de análisis iniciado en los módulos anteriores. En esta etapa, el enfoque principal es la **Visualización de Datos** utilizando las librerías **Matplotlib** y **Seaborn**. 

A partir del dataset limpio y optimizado en el Módulo 4 (`dataset_final_ecommerce.csv`), se han generado una serie de visualizaciones estratégicas para interpretar el comportamiento de los clientes, identificar tendencias de gasto y segmentar el mercado de manera visual y efectiva.

🔗 **Repositorio del Proyecto:** [https://github.com/rbetis35/modulo5pythonsence](https://github.com/rbetis35/modulo5pythonsence)

---

## 🎯 Objetivos de Visualización
*   **Análisis Univariado:** Comprender la distribución individual de variables críticas como la Edad y el Monto de Compra.
*   **Análisis Bivariado:** Explorar la relación entre variables (ej. Edad vs. Gasto) para identificar patrones de consumo.
*   **Segmentación Visual:** Comparar el desempeño de diferentes categorías de clientes (Premium vs. Regular) y zonas geográficas.
*   **Personalización de Reportes:** Aplicar estilos, paletas de colores (`viridis`, `magma`, `YlGnBu`) y anotaciones para mejorar la legibilidad técnica.

---

## 📂 Estructura del Repositorio

| Archivo | Descripción |
| :--- | :--- |
| `Proyecto_Modulo_5.ipynb` | **Notebook Principal.** Contiene los gráficos, el código y las conclusiones analíticas. |
| `dataset_final_ecommerce.csv` | Dataset de entrada (generado y optimizado en el Módulo 4). |
| `README.md` | Documentación del proyecto y guía de ejecución. |

---

## 📊 Visualizaciones Incluidas

1.  **Histograma de Edades:** Análisis de la demografía de la base de clientes.
2.  **Boxplot de Monto Total:** Visualización de la dispersión y validación de la ausencia de outliers críticos.
3.  **Scatter Plot (Dispersión):** Relación entre Edad y Gasto, segmentado por Categoría de Cliente.
4.  **Gráfico de Barras por Ciudad:** Comparativa de gasto promedio por ubicación geográfica.
5.  **Heatmap (Mapa de Calor):** Cruce de Rango Etario y Categoría para identificar los nichos de mayor valor.

---

## 🛠️ Tecnologías Utilizadas
*   **Python 3.13**
*   **Pandas:** Para la manipulación y preparación de las tablas de datos.
*   **Matplotlib:** Librería base para la creación de figuras y ejes.
*   **Seaborn:** Para visualizaciones estadísticas avanzadas y estilos profesionales.

---

## ⚙️ Instalación y Ejecución
Para visualizar los gráficos correctamente en su entorno local, instale las dependencias necesarias:

```bash
py -m pip install pandas matplotlib seaborn openpyxl
