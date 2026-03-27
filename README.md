# Evaluación final de Módulo 3: Data Analysis

## Customer Loyalty & Flight Activity

Este repositorio forma parte de una evaluación práctica en la que se realiza un análisis completo de datos siguiendo distintas fases del proceso analítico.

---

## Objetivos:

* Comprender la estructura de los datos
* Realizar limpieza y preparación (*gestión de nulos*)
* Analizar variables numéricas y categóricas
* Evaluar relaciones entre variables
* Visualizar resultados de forma clara

---

## Estructura del repositorio

```
├── files_limpios/
│   ├── customer_loyalty_history_limpio.csv
│   ├── customer_flight_activity_limpio.csv
│   ├── customer_completo_limpio.csv
│
│── Customer Loyalty History.csv
│── Customer Flight Activity.csv
│
│── Fase_l_Exploracion_Limpieza.ipynb
│── Fase_ll_Analisis_Estadistico.ipynb
│── Fase_lll_Visualizacion.ipynb
│── Fase_lV_Evaluacion_variables.ipynb
│
└── README.md
```

---

## Metodología

La evaluación se divide en 4 fases principales:

---

### 🔹 Fase 1: Exploración de datos (EDA) y Limpieza

* Revisión de estructura del dataset
* Identificación de tipos de datos
* Detección de valores nulos
* Análisis general de variables
* Tratamiento de valores nulos
* Identificación de outliers (IQR y boxplots)
* Corrección de inconsistencias (ej: salarios negativos)
* Preparación de variables para análisis

---

### 🔹 Fase 2: Análisis estadístico

* Agrupación de datos por categorías
* Cálculo de estadísticas descriptivas:

  * media
  * mediana
  * desviación estándar
* Valores atípicos
* Análisis de correlación entre variables

---

### 🔹 Fase 3: Visualización

* Uso de **Matplotlib** y **Seaborn**
* Gráficos de:

  * distribución
  * comparaciones entre grupos
  * evolución de variables
* Uso de `hue` para análisis multivariable

---

### 🔹 Fase 4: Diferencias en Reservas de Vuelos por Nivel Educativo

* Agrupación de datos
* Aplicación de análisis estadístico y visualización para analizar variables específicas
* Evaluación de diferencias entre grupos (ej: nivel educativo)

---

## Tecnologías utilizadas

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

---

## Datos

Los datos utilizados provienen de:

* Customer Loyalty History
* Customer Flight Activity

Tras el proceso de limpieza, se generaron versiones depuradas en la carpeta:

```
files_limpios/
```
---

## Cómo ejecutar los notebooks

Para poder ejecutar correctamente los notebooks de este repositorio, sigue los siguientes pasos:

### 1. Clonar o descargar el repositorio

Asegúrate de tener todos los archivos del repositorio, incluyendo:

* archivos `.ipynb`
* archivos `.csv`
* la carpeta `files_limpios/`

---

### 2. Verificar la estructura de carpetas

Es importante mantener la estructura original del repositorio, ya que los notebooks cargan los archivos `.csv` desde rutas relativas.

---

### 3. Instalar las librerías necesarias

Cada notebook incluye al inicio las librerías requeridas. En general, necesitarás instalar:

```id="z9x1p2"
pip install pandas numpy matplotlib seaborn
```
---

### 4. Ejecutar los notebooks

1. Abre Jupyter Notebook o Jupyter Lab
2. Navega a la carpeta `notebooks/`
3. Abre el notebook correspondiente a la fase que quieras ejecutar
4. Ejecuta las celdas en orden (de arriba hacia abajo)

---

### 5. Consideraciones importantes

* Asegúrate de que los archivos `.csv` estén en las rutas correctas antes de ejecutar el código
* Ejecuta las celdas en orden para evitar errores por variables no definidas
* Si modificas rutas o nombres de archivos, actualiza también el código

---

## Conclusiones

