# Heart Attack Risk Prediction Project

This repository contains the development of a project aimed at predicting the risk of heart attacks. Throughout the project, various classification models are explored and trained using multiple algorithms and scaling techniques. Additionally, hyperparameter optimization is performed, and model performances are compared through cross-validation and optimization techniques.

## Practical 1: Data Exploration and Model Training

In the first practical session, data exploration is conducted, and a series of predictive models are trained using different classification algorithms. The models considered include:

- **Logistic Regression**
- **Decision Trees**
- **Support Vector Machines (SVM)**
- **K-Nearest Neighbors (KNeighbors)**
- **Random Forest**
- **AdaBoost**

### Scaling Techniques Used:
- **StandardScaler**
- **MinMaxScaler**
- **RobustScaler**

### Performance Evaluation:
Each model is evaluated in terms of predictive performance using metrics such as precision, recall, F1-score, and accuracy. Models are assessed with different combinations of scalers and algorithms.

---

## Practical 2: Model Optimization and Evaluation

The second practical session involves continuing the analysis and optimization of the models using data from the first session. The tasks to be performed include:

1. **Algorithm Selection:**
   - Selection of one algorithm based on distances, one based on rules, one using vector transformation, one ensemble method via boosting, and another via bagging.
   - Training each algorithm with default parameters, followed by evaluation using cross-validation.
   - Overfitting analysis by comparing training and validation metrics.

2. **Hyperparameter Exploration:**
   - Testing different hyperparameters on the aforementioned algorithms to explore their impact on performance.

3. **Hyperparameter Optimization:**
   - For the best-performing model, hyperparameter optimization is carried out using three approaches:
     - **Bayesian Optimization**
     - **GridSearch**
     - **HalvingGridSearch**

4. **Evaluation with TPOT:**
   - Running **TPOT** to perform self-learning of models and compare model performances.

