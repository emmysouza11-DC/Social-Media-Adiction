# Social Media & Mental Health

Análisis exploratorio de la relación entre el uso de redes sociales y la 
depresión, basado en datos de encuesta real.

**Fuente:** [Social Media and Mental Health](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health) — Kaggle  
**Muestra:** 478 participantes, encuesta universitaria

## Objetivo

Explorar si el tiempo de uso, la búsqueda de validación y otros comportamientos 
en redes sociales se correlacionan con niveles de depresión reportados.

## Estructura

Social-Media-Adiction/
├── data/
│   ├── raw/          # CSV original (no versionado)
│   └── processed/    # Dataset limpio
├── notebooks/        # Análisis en Jupyter
│   ├── 01_exploracion.ipynb
│   ├── 02_limpieza.ipynb
│   └── 03_analisis.ipynb
├── src/              # Funciones reutilizables
├── reports/
│   ├── figures/      # Gráficos exportados
│   └── preguntas_analisis.md
├── .gitignore
├── README.md
└── requirements.txt

## Stack

- Python 3.x
- pandas, matplotlib, seaborn
- Jupyter Notebook

## Estado

En progreso — fase de análisis.