#  Titanic Survival Prediction — Decision Tree

Proyecto de **Machine Learning** enfocado en la predicción de supervivencia de pasajeros del Titanic utilizando un **Árbol de Decisión**.  
El objetivo es comprender qué variables influyeron más en la supervivencia y cómo un modelo interpretable puede ayudar a explicar decisiones.

---

##  Objetivo del proyecto

- Analizar el dataset del Titanic
- Entrenar un modelo de **clasificación supervisada**
- Evaluar el desempeño del modelo
- Interpretar los resultados mediante visualizaciones
- Extraer conclusiones basadas en datos históricos

---

##  Dataset

- **Fuente**: Dataset clásico del Titanic
- **Variable objetivo**: `Survived`
- **Principales features**:
  - Sex
  - Pclass
  - Age
  - Fare
  - Family size (features derivadas)

El dataset se incluye en el repositorio como:






---

## ⚙️ Metodología

1. **Carga y exploración de datos**
2. **Preprocesamiento**
   - Selección de variables
   - Manejo de valores faltantes
   - Codificación de variables categóricas
3. **Entrenamiento del modelo**
   - `DecisionTreeClassifier` (scikit-learn)
4. **Evaluación**
   - Matriz de confusión
   - Versión normalizada
5. **Interpretabilidad**
   - Visualización del árbol de decisión
   - Importancia de variables (`feature_importances_`)

---

## Resultados principales

- El **género** fue la variable más influyente en la supervivencia
- La **clase del pasajero** y la **edad** también tuvieron un impacto significativo
- El árbol de decisión permite entender claramente las reglas de clasificación
- Se observa el compromiso entre interpretabilidad y complejidad del modelo

---

## Interpretación del modelo

- Los nodos superiores del árbol representan las decisiones más relevantes
- El uso de un árbol de decisión facilita la explicación del modelo a perfiles no técnicos
- El análisis confirma patrones históricos conocidos del desastre

---

## Tecnologías utilizadas

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

##  Cómo ejecutar el proyecto

1. Clonar el repositorio o descargar los archivos
2. Abrir el notebook:


