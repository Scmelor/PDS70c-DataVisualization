# PDS70c-DataVisualization

Este repositorio contiene notebooks de Python para la visualización de resultados derivados del modelado termoquímico del disco circumplanetario de PDS 70c, utilizando los códigos ProDiMoPy y PsyCo.

## Contenido

- `Script_PsyCo_PDS-70.ipynb`: Notebook que permite graficar la evolución orbital y la composición química (hielos y gases) de las lunas simuladas en el modelo de formación lunar con PsyCo.
- `Plots_PDS70.ipynb`: Notebook de visualización de los espectros sintéticos, temperaturas, abundancias y mapas 2D del modelo ProDiMo para el disco circumplanetario.

## Descripción

Este repositorio hace parte del proyecto de tesis de maestría:  
**“Caracterización del Disco Protolunar PDS 70 c a través de Modelado Termoquímico y sus Firmas Espectrales”**  
Universidad de Antioquia, 2025.  

Debido a que el código fuente de ProDiMo no es de libre distribución, este repositorio solo incluye herramientas de visualización y análisis de los datos ya simulados.

## Dependencias

Para ejecutar los notebooks se requiere Python ≥3.8 y las siguientes librerías:

- numpy
- matplotlib
- pandas
- seaborn
- astropy
- netCDF4
- h5py

Puedes instalar las dependencias mediante:

```bash
pip install -r requirements.txt
