## [Credit Risk]

[Este proyecto desarrolla un modelo de Machine Learning Supervisado para clasificar el riesgo de impago en clientes bancarios, permitiendo una evaluación eficiente y eficaz con mejores herramientas]

---

## Resultados

* **Métrica Principal:** [Con el modelo de Random Forest Optimizado, los creditos mal aprobados solo corresponden a un 10,5%, mejorando del 15%]
* **Insight de Negocio:** [Actualmente, la medición del riesgo se basaba en estimaciones en las variables, ahora esta herramienta determina que variables son importantes a partir de la evidencia de los datos]
* **Valor Aportado:** [Se entrega un Modelo optimizado con los mejores hiperparámetros]

---

## Tecnologías y Librerías Utilizadas

* **Lenguaje:** Python 3.0
* **Análisis y Manipulación de Datos:** Pandas, NumPy
* **Visualización:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn, RandomForestClassifier, LogisticRegression
* **Entorno de Desarrollo:** GoogleColaboratory

---

## Estructura del Repositorio

```text
├── data/                  	# Conjuntos de datos (fuente original: https://www.kaggle.com/datasets/daniellopez01/credit-risk)
├── notebooks/             	# Cuadernos de GoogleColaboratory explicativos
│   └── 01_Credit Risk.ipynb    # Análisis Exploratorio de Datos (EDA), Limpeza, Entrenamiento, Evaluación y Selección de Modelos
├── src/                   	# Scripts de Python organizados (.py)
├── .gitignore             	# Archivos excluidos del control de versiones
├── README.md              	# Documentación principal del proyecto
└── requirements.txt      	# Lista de dependencias del proyecto