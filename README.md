# Integrador_Grupo30_UTN
# Readme - Proyecto Integrador: Predicción de Tipo de Obesidad según Hábitos de Vida

Este repositorio contiene el **Trabajo Práctico Integrador** para la **Diplomatura en Ciencia de Datos y Análisis Avanzado** (UTN Buenos Aires). El objetivo del proyecto es entrenar modelos de Machine Learning para predecir el nivel de obesidad de una persona basándose en sus hábitos de vida y datos antropométricos.

---

## 👥 Miembros del Equipo
* ANA LAURA CAO
* FEDERICO TRANI
* MARIA PIA PEDROSO
* HERNAN RODRIGUES NEVES
* ESTEFANIA SANGUINETTI

---

## 📊 Contexto y Dataset
El sobrepeso ha incrementado notablemente en las últimas décadas a nivel mundial. Este dataset recopila información real de hábitos de vida de personas de **Perú, Colombia y México**, junto con sus niveles de obesidad correspondientes.

* **Fuente del Dataset:** [UCI Machine Learning Repository - Estimation of obesity levels based on eating habits and physical condition (DOI: 10.24432/C5H31Z)](https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition).
* **Archivo utilizado:** `ObesityDataSet_raw_and_data_sinthetic.xlsx` (incluido en la raíz del repositorio).
* **Variable objetivo:** `NObeyesdad` (Clasificada en 7 niveles: Bajo peso, Peso normal, Sobrepeso Nivel I/II, y Obesidad Tipo I/II/III).

---

## 🛠️ Librerías Principales
El proyecto utiliza Python y las siguientes librerías para el análisis y modelado:
* **Manipulación y Análisis:** `pandas`, `numpy`, `time`, `openpyxl`
* **Visualización:** `matplotlib`, `seaborn`
* **Machine Learning (`scikit-learn`):** 
  * Preprocesamiento: `StandardScaler`, `OneHotEncoder`, `ColumnTransformer`, `Pipeline`, `SimpleImputer`
  * Modelos: `LogisticRegression`, `DecisionTreeClassifier`, `RandomForestClassifier`
  * Evaluación: `accuracy_score`, `confusion_matrix`, `classification_report`, `roc_auc_score`, `f1_score`, etc.

---

## 🚀 Instrucciones para Correr el Proyecto

Puedes ejecutar este proyecto de forma interactiva mediante Google Colab o localmente. Como el dataset ya se encuentra en el repositorio, se leerá automáticamente.

### Opción 1: Ejecutar en Google Colab (Recomendado)
1. Abre el notebook `TP_final_UTN.ipynb` en Google Colab (puedes abrirlo directamente desde el botón de GitHub en Colab).
2. Asegúrate de que el archivo `ObesityDataSet_raw_and_data_sinthetic.xlsx` esté en la misma ruta de trabajo que el notebook.
3. Ejecuta las celdas secuencialmente desde la **Sección 0** (Configuración Inicial) hasta finalizar el entrenamiento y evaluación de los modelos.

### Opción 2: Ejecutar Localmente
1. Clona este repositorio en tu máquina:
   ```bash
   git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)
   cd tu-repositorio
