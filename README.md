# Proyecto de Predicción de Riesgo de Ataque Cardíaco

Este repositorio contiene el desarrollo de un proyecto de predicción de riesgo de ataque cardiaco. A lo largo del proyecto se exploran y entrenan distintos modelos de clasificación utilizando varios algoritmos y técnicas de escalado. Además, se optimizan hiperparámetros y se comparan los rendimientos de los modelos a través de cross-validation y técnicas de optimización.

## Práctico 1: Exploración de datos y entrenamiento de Modelos

En el primer práctico, se realiza una exploración de los datos y se entrena una serie de modelos predictivos utilizando distintos algoritmos de clasificación. Los modelos considerados son los siguientes:

- **Regresión Logística**
- **Árboles de Decisión**
- **Máquinas de Soporte Vectorial (SVM)**
- **K-Nearest Neighbors (KNeighbors)**
- **Random Forest**
- **AdaBoost**

### Escaladores Utilizados:
- **StandardScaler**
- **MinMaxScaler**
- **RobustScaler**

### Evaluación de Desempeños:
Cada modelo se evalúa en términos de su rendimiento predictivo utilizando métricas como precisión, recall, F1-score y accuracy. Se evaluan con diferentes combinaciones de escaladores y modelos.

---

## Práctico 2: Optimización y evaluación de modelos

El segundo práctico consiste en continuar el análisis y optimización de los modelos utilizando los datos del primer práctico. Las tareas a desarrollar incluyen:

1. **Selección de Algoritmos:**
   - Selección de un algoritmo basado en distancias, uno basado en reglas, uno de transformación vectorial, un método de ensamble vía boosting y otro vía bagging.
   - Entrenamiento de cada algoritmo con sus parámetros por defecto, seguido de la evaluación mediante cross-validation.
   - Evaluación del sobreajuste mediante la comparación de las métricas de entrenamiento y validación.

2. **Exploración de hiperparámetros:**
   - Probar diferentes hiperparámetros en los algoritmos anteriores para explorar cómo afectan su rendimiento.

3. **Optimización de Hiperparámetros:**
   - Para el modelo con mejor rendimiento, se realiza una optimización de hiperparámetros utilizando tres enfoques:
     - **Optimización Bayesiana**
     - **GridSearch**
     - **HalvingGridSearch**

4. **Evaluación con TPOT:**
   - Ejecución de **TPOT** para realizar self-learning de modelos y comparar los rendimientos de los modelos.
