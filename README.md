# Hola, soy Juan Diego Taborda 👋

### Data Scientist · Data Analyst · Python Developer

*Medellín, Colombia 🇨🇴 · Abierto a trabajo remoto y reubicación*

[![LinkedIn](https://img.shields.io/badge/LinkedIn-juandiegotabordaroldan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/juandiegotabordaroldan)
[![Email](https://img.shields.io/badge/Email-juandiego276@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:juandiego276@gmail.com)
[![Azure AZ-900](https://img.shields.io/badge/Azure-AZ--900_Certified-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://learn.microsoft.com/en-us/certifications/azure-fundamentals/)

---

## 🏗️ Sobre mí

Soy **Ingeniero de Telecomunicaciones con énfasis en Ciencia de Datos** (Universidad de Medellín). Me dedico a convertir datos en decisiones: construyo modelos de machine learning, pipelines de datos y aplicaciones analíticas que resuelven problemas de negocio reales.

Mi experiencia práctica viene de entornos de producción del sector financiero y asegurador: en **Protección S.A.** desarrollé un pipeline ETL diario en BigQuery (Python) con detección automática de fallos y notificación al responsable; en **Summa (Grupo Argos)** escalé una API ETL de uso interno a toda la organización, alimentando tableros de Power BI.

```
📍 Medellín, Colombia · 🌎 Abierto a remoto y reubicación
🎓 Ing. de Telecomunicaciones — Universidad de Medellín
📊 Bootcamp Análisis de Datos (159h) — Talento Tech / U. de Antioquia
📘 IBM Data Engineering Professional Certificate — Coursera (en curso)
🗣️ Español nativo · Inglés B2
```

---

## 🛠️ Stack Técnico

**Lenguajes y consultas**
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org)

**Machine Learning y análisis**
[![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)](https://scikit-learn.org)
[![LightGBM](https://img.shields.io/badge/LightGBM-9B59B6?style=for-the-badge&logo=microsoft&logoColor=white)](https://lightgbm.readthedocs.io)
[![pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org)
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)](https://numpy.org)

**Datos y nube**
[![Google BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white)](https://cloud.google.com/bigquery)
[![Azure](https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)](https://azure.microsoft.com)
[![KNIME](https://img.shields.io/badge/KNIME-FDD800?style=for-the-badge&logo=knime&logoColor=black)](https://www.knime.com)

**Visualización y despliegue**
[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com)
[![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)](https://streamlit.io)

---

## 🚀 Proyectos Destacados

### 1 · 💊 Análisis de Importaciones Farmacéuticas con ML
> **Sector:** Salud / Cadena de suministro · **Stack:** Python, LightGBM, scikit-learn, Streamlit

Sistema de ML que predice atributos (principio activo, fabricante, marca) y precio de importaciones farmacéuticas a partir de su perfil logístico, segmentado por tipo de producto. Pipeline completo: EDA → tratamiento de variables → modelos LightGBM por segmento → app Streamlit multipágina.

**Resultados:** hasta **94–97% de accuracy** en clasificación (segmento Oncológico) y **R² de 0.73–0.75** en predicción de precio. El tratamiento correcto de identificadores como categóricos y la transformación logarítmica del precio llevaron el desempeño de cercano al azar a los valores actuales.

🔗 [**Ver repositorio →**](https://github.com/JuanDiego076/pharma-imports-ml)

### 2 · 🏠 Clasificación Socioeconómica por Patrones de Uso de TIC
> **Sector:** Política pública / Telecom · **Stack:** Python, scikit-learn, Bagging, Random Forest, Jupyter

Pipeline de clasificación multiclase para predecir el estrato socioeconómico de hogares a partir de su uso de TIC (internet, TV, smartphones). Construido sobre **ENDUTIH 2024** — encuesta nacional de hogares de México (58.080 registros).

Pipeline completo: EDA → manejo de nulos (ColumnTransformer + imputers) → comparación de 5 modelos (Decision Tree, Bagging, Random Forest, AdaBoost, XGBoost) → ajuste de hiperparámetros con `RandomizedSearchCV` → validación cruzada estratificada 10-fold.

🔗 [**Ver repositorio →**](https://github.com/JuanDiego076/socioeconomic-classification-via-ict)

### 3 · 📝 Clustering y Clasificación NLP de Reseñas de Medicamentos
> **Sector:** Salud / NLP · **Stack:** Python, scikit-learn, DBSCAN, TF-IDF, PCA, LDA

Estudio NLP en dos partes sobre el dataset DrugLib.com (UCI ML Repository): clustering no supervisado de reseñas de pacientes + comparación de reducción de dimensionalidad para clasificación de efectividad en 5 clases. Evalúa K-Means, Agglomerative y DBSCAN para clustering; PCA, LDA y SFFS para clasificación supervisada.

**Resultados:** DBSCAN alcanza un Silhouette de **0.707** en clusters semánticos de texto; PCA (47.5%) supera a LDA supervisado (27.6%), confirmando fronteras de clase no lineales en el espacio TF-IDF.

🔗 [**Ver repositorio →**](https://github.com/JuanDiego076/drug-review-nlp-clustering)

### 4 · 🏦 Pipeline ETL — Bancos más grandes del mundo
> **Stack:** Python, BeautifulSoup, SQLite, pandas

Pipeline ETL que hace web scraping de los bancos más grandes del mundo, convierte monedas y carga los datos a CSV y SQLite, con logging y manejo de errores.

🔗 [**Ver repositorio →**](https://github.com/JuanDiego076/etl-largest-banks)

---

## 📫 Conectemos

Busco activamente roles **Junior/Mid de Data Scientist, Data Analyst o Data Engineer** donde pueda construir cosas con impacto real. Si trabajas en retos de datos o sistemas de ML, hablemos.

**LinkedIn:** [linkedin.com/in/juandiegotabordaroldan](https://www.linkedin.com/in/juandiegotabordaroldan) · **Email:** juandiego276@gmail.com
