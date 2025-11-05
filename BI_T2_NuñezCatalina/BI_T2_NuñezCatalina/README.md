╔════════════════════════════════════════════════════════════════════╗
    BI_T2_NuñezCatalina — Análisis temporal de                publicaciones de prendas        
╚════════════════════════════════════════════════════════════════════╝

Este proyecto analiza la evolución temporal de publicaciones de prendas utilizando el dataset `outfits.csv`, aplicando tres técnicas de Machine Learning: regresión lineal para identificar tendencias temporales, Random Forest para clasificar publicaciones recientes según características temporales, y K-Means para agrupar periodos con patrones de actividad similares. 

Los resultados entregan información clave para la toma de decisiones en Business Intelligence, revelando patrones de crecimiento, fluctuaciones en la frecuencia de publicaciones y posibles estacionalidades.

Para ejecutar el proyecto, se requiere Python 3.9 o superior y las librerías incluidas en `requirements.txt`; basta con abrir el notebook `BI_T2_NuñezCatalina.ipynb` en Jupyter o Google Colab, asegurarse de tener el archivo `outfits.csv` en el mismo directorio, y ejecutar todas las celdas en orden.
 
 
 Requisitos y versión probada
 ------------------------------------------------------------
 - Versión de Python probada: 3.11.x
 - Instalar dependencias (en Windows/PowerShell):
 
 ```bash
 python -m venv .venv
 .\.venv\Scripts\Activate.ps1
 python -m pip install -r requirements.txt ipykernel
 python -m ipykernel install --user --name bi_t2
 ```
 
 Ejecución
 ------------------------------------------------------------
 - Abrir `BI_T2_NuñezCatalina.ipynb` y seleccionar el kernel `bi_t2`.
 - Asegurar que el archivo de datos esté en la misma carpeta (p.ej. `outfits (1).csv`).