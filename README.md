# 🎮 Minería de Datos — Steam Games Dataset

Repositorio de la **Evaluación 1** de la asignatura Minería de Datos.

## 👥 Integrantes

- Amaro Araneda

## 📦 Dataset

**Steam Games Dataset** — Información de más de 27.000 videojuegos publicados en Steam.

- **Fuente:** Kaggle — https://www.kaggle.com/datasets/nikdavis/steam-store-games
- **Archivo principal:** `steam.csv`
- **Filas:** 27.075
- **Columnas:** 18 (variables numéricas y categóricas)

## 📂 Estructura del Repositorio

```
mineria-datos-steam/
├── README.md
├── data/
│   └── steam.csv
└── notebooks/
    └── analisis_steam_games.ipynb
```

## 📊 Contenido del Notebook

El notebook `analisis_steam_games.ipynb` cubre:

1. Justificación del dataset
2. Carga e inspección inicial
3. Mapeo de datos (diccionario de variables)
4. Revisión de tipos de datos (numérico, categórico, tipo Python)
5. Análisis de valores nulos y duplicados
6. Estadísticas descriptivas
7. Ingeniería de variables (variables derivadas)
8. Análisis univariado (histogramas, boxplots, gráficos de barras)
9. Análisis bivariado (scatterplots, comparaciones por grupo)
10. Análisis de correlación (matriz de Pearson + heatmap)
11. Conclusiones y próximos pasos

## 🔧 Tecnologías

- Python 3
- Pandas, NumPy
- Matplotlib, Seaborn
- Google Colab

## 🌿 Flujo de Trabajo Git

- `main` / `master`: rama principal con entregables finales
- `dev`: rama de desarrollo activo
- Pull Requests desde `dev` → `main` al finalizar cada entrega
