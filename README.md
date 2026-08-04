# 🌦️ WeatherAUS Data Mining

> **Proyecto de Minería de Datos desarrollado sobre el conjunto de datos WeatherAUS, aplicando la metodología CRISP-DM para el análisis, preparación y modelado de datos climáticos mediante técnicas de aprendizaje automático y visualización de resultados.**

---

# 📌 Tabla de Contenidos

- [Acerca del Proyecto](#-acerca-del-proyecto)
- [Objetivos](#-objetivos)
- [Dataset](#-dataset)
- [Metodología](#-metodología)
- [Contenido del Cuaderno](#-contenido-del-cuaderno)
- [Modelos Implementados](#-modelos-implementados)
- [Resultados del Proyecto](#-resultados-del-proyecto)
- [Dashboard Ejecutivo](#-dashboard-ejecutivo)
- [Tecnologías Utilizadas](#-tecnologías-utilizadas)
- [Estructura del Repositorio](#-estructura-del-repositorio)
- [Cómo utilizar este repositorio](#-cómo-utilizar-este-repositorio)
- [Autor](#-autor)

---

# 📖 Acerca del Proyecto

Este proyecto corresponde al desarrollo de un proceso completo de **Minería de Datos** utilizando el conjunto de datos **WeatherAUS**, siguiendo la metodología **CRISP-DM** para comprender, preparar y analizar información climática proveniente de distintas estaciones meteorológicas de Australia.

El objetivo principal consiste en aplicar técnicas de análisis exploratorio y aprendizaje automático para identificar patrones en los datos meteorológicos, construir modelos predictivos y evaluar su desempeño mediante distintos algoritmos de clasificación, regresión y agrupamiento.

Como complemento al análisis realizado en Python, el proyecto incorpora un **Dashboard Ejecutivo en Power BI**, diseñado para facilitar la interpretación visual de los principales resultados obtenidos.

---

# 🎯 Objetivos

- Analizar el comportamiento de las variables meteorológicas presentes en el conjunto de datos.
- Preparar los datos mediante procesos de limpieza, transformación y selección de variables.
- Implementar y evaluar diferentes modelos de aprendizaje automático.
- Comparar el desempeño de algoritmos supervisados y no supervisados.
- Interpretar los resultados obtenidos mediante métricas y visualizaciones.
- Complementar el análisis con un Dashboard Ejecutivo desarrollado en Power BI.

---

# 📊 Dataset

El proyecto utiliza el conjunto de datos **WeatherAUS**, ampliamente utilizado en investigaciones y proyectos de minería de datos relacionados con el análisis climático.

El dataset contiene información meteorológica histórica registrada en distintas localidades de Australia, incluyendo variables como:

- Temperatura máxima y mínima.
- Humedad.
- Presión atmosférica.
- Velocidad y dirección del viento.
- Precipitaciones.
- Nubosidad.
- Radiación solar.

El análisis se centra principalmente en la predicción de la variable objetivo **RainTomorrow**, además del estudio de la variable continua **RISK_MM** para tareas de regresión.

---

# 🧠 Metodología

El proyecto fue desarrollado siguiendo la metodología **CRISP-DM (Cross Industry Standard Process for Data Mining)**, estructurando el proceso en cinco fases principales:

1. Comprensión del negocio (*Business Understanding*)
2. Comprensión de los datos (*Data Understanding*)
3. Preparación de los datos (*Data Preparation*)
4. Modelado (*Modeling*)
5. Evaluación (*Evaluation*)

> **Nota:** Cada una de estas fases se encuentra desarrollada y documentada detalladamente en el cuaderno Jupyter incluido en este repositorio.

---

# 📓 Contenido del Cuaderno

El notebook **ET_PreparandoDatosClimaticos_DataMining.ipynb** documenta paso a paso todo el proceso de minería de datos desarrollado durante el proyecto, incluyendo:

- Introducción y definición del problema.
- Comprensión del negocio.
- Exploración y comprensión del conjunto de datos.
- Evaluación de la calidad de los datos.
- Análisis Exploratorio de Datos (EDA).
- Identificación de insights relevantes.
- Selección de variables.
- Tratamiento e imputación de valores faltantes.
- Codificación de variables categóricas.
- Transformación de variables temporales.
- Tratamiento de valores atípicos (Outliers).
- Escalamiento de datos.
- División en conjuntos de entrenamiento y prueba.
- Implementación de modelos supervisados.
- Implementación de modelos no supervisados.
- Evaluación de modelos mediante distintas métricas.
- Interpretación de resultados y conclusiones.

---

# 🤖 Modelos Implementados

Durante el proyecto se implementaron distintos algoritmos de minería de datos con el propósito de abordar problemas de clasificación, regresión y agrupamiento.

| Tipo | Algoritmos |
| :--- | :--- |
| **Clasificación** | Naive Bayes, Árbol de Decisión, Support Vector Machine (SVM) |
| **Regresión** | Regresión Lineal |
| **Clustering** | K-Means |

Cada modelo fue evaluado mediante métricas apropiadas para su tipo de problema, permitiendo comparar su desempeño e interpretar los resultados obtenidos.

---

# 📌 Resultados del Proyecto

El desarrollo de este proyecto permitió recorrer de manera completa el proceso de minería de datos propuesto por la metodología **CRISP-DM**, obteniendo resultados relevantes tanto desde el punto de vista analítico como predictivo.

Entre los principales logros alcanzados destacan:

- ✅ Comprensión del comportamiento de las variables meteorológicas presentes en el conjunto de datos WeatherAUS.
- ✅ Identificación de problemas de calidad de datos, tales como valores faltantes, variables redundantes y posibles casos de fuga de información (*Data Leakage*).
- ✅ Preparación del conjunto de datos mediante procesos de limpieza, transformación, codificación y escalamiento para mejorar su calidad antes del modelado.
- ✅ Implementación y comparación de distintos algoritmos de clasificación, regresión y clustering, evaluando sus fortalezas y limitaciones mediante métricas específicas para cada problema.
- ✅ Identificación de patrones y relaciones entre variables meteorológicas a partir del análisis exploratorio de datos y de los modelos desarrollados.
- ✅ Desarrollo de un Dashboard Ejecutivo en Power BI para comunicar de forma visual los principales indicadores y resultados obtenidos durante el análisis.

El detalle completo del proceso, las decisiones metodológicas adoptadas y la interpretación de los resultados se encuentra documentado en el notebook principal del proyecto.

---

# 📊 Dashboard Ejecutivo

Como complemento al análisis desarrollado en Python, el proyecto incorpora un **Dashboard Ejecutivo en Power BI**, orientado a facilitar la exploración e interpretación de los principales resultados obtenidos durante el proceso de minería de datos.

El dashboard permite visualizar de manera gráfica indicadores relevantes, métricas de análisis y resultados derivados de los modelos implementados, proporcionando una visión resumida y de apoyo para la toma de decisiones.

---

# 🛠️ Tecnologías Utilizadas

### Lenguaje y Entorno

- Python
- Jupyter Notebook

### Manipulación y Análisis de Datos

- Pandas
- NumPy

### Minería de Datos y Machine Learning

- Scikit-learn

### Visualización de Datos

- Matplotlib
- Seaborn
- Power BI

---

# 📁 Estructura del Repositorio

```text
WeatherAUS-Data-Mining/
│
├── ET_PreparandoDatosClimaticos_DataMining.ipynb
│   # Notebook principal con el desarrollo completo del proyecto
│
├── DashboardEjecutivo_DatosClimaticos_MineriaDatos.pbix
│   # Dashboard Ejecutivo desarrollado en Power BI
│
├── Dataset/
│   # Conjunto de datos utilizado durante el análisis
│
└── README.md
│   # Documentación general del proyecto
```

---

# 🚀 Cómo utilizar este repositorio

Para comprender el desarrollo del proyecto se recomienda seguir el siguiente orden:

1. Leer este README para conocer el contexto y alcance del proyecto.
2. Revisar el notebook **ET_PreparandoDatosClimaticos_DataMining.ipynb**, donde se documenta detalladamente cada fase de la metodología CRISP-DM.
3. Explorar el archivo **DashboardEjecutivo_DatosClimaticos_MineriaDatos.pbix** para visualizar los resultados obtenidos mediante Power BI.

---

# 👨‍💻 Autor

**Leonel Vittorio González Escalona**

Proyecto desarrollado como parte de la asignatura **Minería de Datos**, aplicando técnicas de análisis exploratorio de datos, preparación de datos, aprendizaje automático y visualización de información para resolver un problema de análisis climático utilizando la metodología **CRISP-DM**.
