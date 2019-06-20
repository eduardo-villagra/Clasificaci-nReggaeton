# Clasificación Reggaeton

Para este estudio se siguió la siguiente estructura:

- Leer Datos 
- análisis descriptivo inicial
- análisis descriptivo gráfico
- Ingeniería de variables
- Machine Learning

En la Sección de Machine Learning se pusieron a competir 11 modelos:

- Random Forest
- KNN
- Logistic Regression
- XGB
- Gradient Boosting
- SVC
- Extra Trees
- AdaBoost
- GaussianNB
- Gaussian Process
- Bagging

Las etapas del modelado son las siguietes:

- 1) Entrenamiento con todas la variables y sólo con los modelos inicializados (se comparan en entrenamiento).
- 2) Entrenamiento de modelos inicializados pero con selección de variables. 
- 3) Se eligen los mejores 4 modelos y se cambian sus hiperparámetros.
- 4) Se elijen los mejores dos modelos y se comparan los resultados en test. 
- 4) Se elige mejor modelo en test para la clasificación final.

(La métrica utilizada para comparar los modelos será el índice Kappa,dado que las clases no están balanceadas)
