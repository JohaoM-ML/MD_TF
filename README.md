# Análisis Climático y Producción Agrícola en el Perú (2020–2025)

**Trabajo Final — Minería de Datos**

##  Descripción

Este proyecto aplica técnicas de **Minería de Datos** para analizar la relación entre variables climáticas (obtenidas de la API NASA POWER) y la producción agrícola en el Perú durante el período 2020–2025.

Se realizaron las siguientes etapas del pipeline de datos:

-  **Adquisición de datos** desde NASA POWER API
-  **Limpieza y preprocesamiento** de datos climáticos y agrícolas
-  **Integración y merging** de datasets heterogéneos
-  **Análisis Exploratorio de Datos (EDA)** con visualizaciones profesionales
-  **Ingeniería de atributos y escalado** (RobustScaler)
-  **Modelado predictivo** mediante técnicas de minería de datos

##  Estructura del Proyecto

```
 MD_TF
 ┣  DM_TF (2).ipynb               ← Notebook principal con todo el pipeline
 ┣  informe_dm.tex                 ← Informe académico en LaTeX
 ┣  Analisis_Climatico_Peru.xlsx   ← Datos climáticos crudos
 ┣  DF_LIMPIO_2020_2025.csv        ← Dataset limpio
 ┣  DF_INTEGRADO_2020_2025.csv     ← Dataset integrado (clima + agricultura)
 ┣  DF_MENSUAL_2020_2025.csv       ← Dataset mensualizado
 ┣  DF_MENSUAL_SCALED_2020_2025.csv← Dataset escalado
 ┣  DF_ACUMULADO_2020_2025.csv     ← Dataset acumulado
 ┣  DF_FINAL_2020_2025.xlsx        ← Dataset final para modelado
 ┗  README.md
```

##  Tecnologías Utilizadas

- **Python** (pandas, numpy, scikit-learn, matplotlib, seaborn)
- **Jupyter Notebook**
- **NASA POWER API**
- **LaTeX** para el informe académico

##  Cómo Ejecutar

1. Clona el repositorio:
   ```bash
   git clone https://github.com/JohaoM-ML/MD_TF.git
   ```
2. Abre el notebook principal:
   ```bash
   jupyter notebook "DM_TF (2).ipynb"
   ```

## Autor

**Johao Mendoza** — Trabajo Final de Data Mining
