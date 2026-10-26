# Integrador_Grupo30_UTN
# Readme - Proyecto Integrador: Predicción de Tipo de Obesidad según Hábitos de Vida

Este repositorio contiene el **Trabajo Práctico Integrador** para la **Diplomatura en Ciencia de Datos y Análisis Avanzado** (UTN Buenos Aires). El objetivo del proyecto es entrenar modelos de Machine Learning para predecir el nivel de obesidad de una persona basándose en sus hábitos de vida y datos antropométricos.

---

## 👥 Miembros del Equipo
* ANA LAURA CAO
* FEDERICO TRANI
* MARIA PIA PEDROSO[cite: 23]
* HERNAN RODRIGUES NEVES[cite: 23]
* ESTEFANIA SANGUINETTI[cite: 23]

---

## 📊 Contexto y Dataset
El sobrepeso ha incrementado notablemente en las últimas décadas a nivel mundial. Este dataset recopila información real de hábitos de vida de personas de **Perú, Colombia y México**, junto con sus niveles de obesidad correspondientes[cite: 23].

* **Fuente del Dataset:** [UCI Machine Learning Repository - Estimation of obesity levels based on eating habits and physical condition (DOI: 10.24432/C5H31Z)](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition)[cite: 23].
* **Dimensiones:** 2,111 filas y 17 columnas[cite: 23].
* **Variable objetivo:** `NObeyesdad` (Clasificada en 7 niveles: Bajo peso, Peso normal, Sobrepeso Nivel I/II, y Obesidad Tipo I/II/III)[cite: 23].

---

## 🛠️ Librerías Principales
El proyecto utiliza Python y las siguientes librerías para el análisis y modelado:
* **Manipulación y Análisis:** `pandas`, `numpy`, `time`[cite: 23]
* **Visualización:** `matplotlib`, `seaborn`[cite: 23]
* **Machine Learning (`scikit-learn`):** 
  * Preprocesamiento: `StandardScaler`, `OneHotEncoder`, `ColumnTransformer`, `Pipeline`, `SimpleImputer`[cite: 23]
  * Modelos: `LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`[cite: 23]
  * Evaluación: `accuracy_score`, `confusion_matrix`, `classification_report`, `roc_auc_score`, `f1_score`, etc.[cite: 23]

---

## 🚀 Instrucciones para Correr el Proyecto

Puedes ejecutar este proyecto de forma interactiva mediante Google Colab o localmente clonando este repositorio.

### Opción 1: Ejecutar en Google Colab (Recomendado)
1. Abre el notebook del proyecto en Google Colab.
2. Asegúrate de tener el archivo del dataset (`ObesityDataSet.csv` o `ObesityDataSet_raw_and_data_sinthetic.csv`) disponible, ya sea:
   * Subiéndolo directamente al entorno de ejecución de Colab[cite: 23].
   * Conectando tu Google Drive y ubicando el archivo dentro de la estructura de carpetas configurada en el script (`UTN_Grupo 30`)[cite: 23].
3. Ejecuta las celdas secuencialmente desde la **Sección 0** (Configuración Inicial) hasta finalizar el entrenamiento y evaluación de los modelos.

### Opción 2: Ejecutar Localmente
1. Clona este repositorio en tu máquina:
   ```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)
   cd tu-repositorio
