# Modelo de Predicción de Partidos - Premier League

Proyecto de Machine Learning para predecir el resultado de partidos de la Premier League inglesa, utilizando datos históricos de encuentros y cuotas de casas de apuestas (odds) como parte del análisis exploratorio y del modelado.

## Descripción

Este repositorio contiene el desarrollo completo de un modelo de clasificación orientado a predecir el resultado de partidos de fútbol (victoria local, empate o victoria visitante). El flujo de trabajo incluye análisis exploratorio de datos (EDA), entrenamiento y comparación de distintos modelos de clasificación, y evaluación de su desempeño mediante métricas estándar (matriz de confusión, curvas ROC, F1-score, importancia de variables, entre otras).

## Estructura del repositorio
├── Dataset/                          # Datos utilizados para el análisis y el entrenamiento
├── Entrega 1er Consolidado/          # Entregable/avance del proyecto
├── Papers/                           # Referencias y material bibliográfico consultado
├── 01_eda.ipynb                      # Notebook de Análisis Exploratorio de Datos (EDA)
├── 02_modelos.ipynb                  # Notebook de entrenamiento y evaluación de modelos
├── DICCIONARIO_DE_DATOS.txt          # Descripción de las variables del dataset
├── feature_importance_final.csv      # Importancia de variables del modelo final
├── resultados_finales.csv            # Resultados finales de las predicciones
└── plot_*.png                        # Gráficos generados durante el análisis y la evaluación

### Gráficos incluidos

- **Balance de clases** – distribución de resultados (local / empate / visitante)
- **Distribución de odds** – análisis de las cuotas de apuestas
- **Métricas clave** – resumen de métricas de evaluación
- **Heatmap de correlación** – correlación entre variables
- **Correlación con la variable objetivo**
- **Matriz de confusión (baseline)**
- **Comparación de modelos**
- **Curvas ROC**
- **Importancia de variables** (incluye una versión v3 de la comparación)
- **Evolución del F1-score**

## Tecnologías utilizadas

- Python
- Jupyter Notebook
- Librerías estándar del ecosistema de ciencia de datos (pandas, scikit-learn, matplotlib/seaborn, etc.)

## Cómo usar este proyecto

1. Clona el repositorio:
```bash
   git clone https://github.com/sebavaldik/Modelo-de-predicci-n-de-partidos-Premier-League.git
   cd Modelo-de-predicci-n-de-partidos-Premier-League
```
2. Instala las dependencias necesarias (se recomienda usar un entorno virtual):
```bash
   pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```
3. Ejecuta los notebooks en orden:
   - `01_eda.ipynb` para el análisis exploratorio de datos.
   - `02_modelos.ipynb` para el entrenamiento, comparación y evaluación de los modelos.

## Metodología

1. **Análisis Exploratorio de Datos (EDA):** revisión del balance de clases, distribución de variables (incluyendo las odds de apuestas) y correlaciones entre atributos.
2. **Modelado:** entrenamiento de distintos algoritmos de clasificación y comparación de su desempeño.
3. **Evaluación:** uso de matriz de confusión, curvas ROC, F1-score e importancia de variables para seleccionar y validar el modelo final.
4. **Resultados:** consolidación de las predicciones finales en `resultados_finales.csv`.

## Diccionario de datos

El archivo [`DICCIONARIO_DE_DATOS.txt`](./DICCIONARIO_DE_DATOS.txt) contiene la descripción detallada de cada variable utilizada en el dataset.

## Autores

- **Sebastián Valdovinos** ([@sebavaldik](https://github.com/sebavaldik))
- **Anakin Benavides**

