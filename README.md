# Análisis Exploratorio de Datos - Netflix Movies and TV Shows

## 📊 Descripción del Proyecto
Este proyecto realiza un análisis exploratorio de datos (EDA) completo del dataset de Netflix Movies and TV Shows, cumpliendo con los requisitos de la Actividad 1 del curso de Python.

## 📁 Contenido del Repositorio
- `netflix_eda.ipynb`: Notebook principal con todo el análisis
- `netflix_titles.csv`: Dataset original de Netflix (descargar de Kaggle)
- `netflix_clean.csv`: Dataset limpio y transformado (generado por el notebook)
- `netflix_eda_report_completo.html`: Reporte completo generado con ydata-profiling
- `README.md`: Este archivo

## 🎯 Objetivos del Análisis
Analizar el catálogo de contenido de Netflix para:
- Entender la composición del catálogo (películas vs series)
- Identificar tendencias temporales en la adición de contenido
- Descubrir patrones en géneros, países productores y duración
- Detectar valores atípicos y anomalías en los datos

## 📋 Requisitos Cumplidos

### 1. ✅ Elección del conjunto de datos
- **Dataset**: Netflix Movies and TV Shows
- **Tamaño**: 8,807 registros × 12 variables
- **Fuente**: [Kaggle](https://www.kaggle.com/datasets/shivamb/netflix-shows)
- **Formato**: CSV
- **Justificación**: Dataset relevante, tamaño adecuado, múltiples tipos de variables

### 2. ✅ Limpieza y transformación de los datos
- Identificación y tratamiento de valores faltantes
- Conversión de tipos de datos
- Creación de nuevas variables derivadas
- Estandarización de formatos

### 3. ✅ Análisis exploratorio de datos (EDA)
- Estadísticas descriptivas completas
- Análisis de distribuciones
- Identificación de patrones y tendencias
- Correlaciones entre variables

### 4. ✅ Visualización de resultados
- Histogramas de distribución
- Gráficos de barras para categorías
- Gráficos de pastel para proporciones
- Boxplots para detección de outliers
- Análisis temporal con gráficos de línea

### 5. ✅ Documentación y presentación
- Código completamente comentado
- Informe con hallazgos principales
- Conclusiones y próximos pasos
- Reporte automático con ydata-profiling

## 🔍 Hallazgos Principales

1. **Composición**: 70% películas, 30% series de TV
2. **Crecimiento**: Expansión exponencial desde 2015
3. **Geografía**: Estados Unidos lidera la producción
4. **Géneros**: Predominan International Movies, Dramas y Comedies
5. **Duración**: Promedio de 99 minutos para películas
6. **Valores faltantes**: Principalmente en director (30%), cast (9.2%)

## 🛠️ Tecnologías Utilizadas
- Python 3.8+
- pandas
- numpy
- matplotlib
- seaborn
- ydata-profiling

## 📦 Instalación de Dependencias
```bash
pip install pandas numpy matplotlib seaborn ydata-profiling
```

## 🚀 Cómo Ejecutar el Proyecto

1. Clonar el repositorio:
```bash
git clone https://github.com/wkatir/netflix-eda-kodigo-ml.git
cd netflix-eda-kodigo-ml
```

2. Descargar el dataset de Kaggle:
   - Ir a https://www.kaggle.com/datasets/shivamb/netflix-shows
   - Descargar `netflix_titles.csv`
   - Colocar en la carpeta del proyecto

3. Instalar dependencias:
```bash
pip install -r requirements.txt
```

4. Ejecutar el notebook:
```bash
jupyter notebook netflix_eda.ipynb
```

## 📈 Resultados
El análisis completo está disponible en:
- **Notebook interactivo**: `netflix_eda.ipynb`
- **Reporte HTML**: `netflix_eda_report_completo.html` (generado al ejecutar el notebook)

## 🔮 Próximos Pasos
1. Análisis predictivo de éxito de contenido
2. Sistema de recomendación basado en características
3. Dashboard interactivo con Plotly/Tableau
4. Análisis de sentimientos en descripciones

## 👤 Autor
Wilmer Henrry Salazar Martinez  
wilmerhenrysalazarmartinez@gmail.com  
20 de julio de 2025

## 📄 Licencia
Este proyecto es parte de una actividad académica.
