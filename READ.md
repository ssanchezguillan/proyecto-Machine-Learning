En este proyecto analizamos el éxito académico de estudiantes utilizando técnicas de aprendizaje automático. Se abordan tres tareas:

-Clasificación: predecir si un estudiante abandona, continúa o se gradúa
-Regresión: predecir la nota media del segundo semestre
-Aprendizaje no supervisado: identificar perfiles de estudiantes

El objetivo es no solo predecir, sino también comprender los factores que influyen en la trayectoria académica.


1.- REQUISITOS
Este proyecto ha sido desarrollado en Python. Es necesario instalar las siguientes librerías:

pip install numpy pandas matplotlib seaborn scikit-learn


2.- CLONAR EL REPOSITORIO


2.- DESCARGAR DATOS
Asegúrate de que el archivo:
    rendimiento_estudiantes_csv

está en la misma carpeta que los notebooks


3.- EJECUTAR preprocesado.ipynb
Este notebook realiza el análisis exploratorio de los datos (EDA) y el preprocesado inicial. En concreto:

- Análisis de valores perdidos  
- Estudio de outliers mediante el criterio IQR  
- Análisis de variables categóricas y continuas  
- Estudio del desbalanceo de la variable objetivo  
- Preparación de los datos para modelado (sin aplicar aún modelos)

Este paso es necesario para comprender la estructura del dataset y justificar las decisiones metodológicas adoptadas en las etapas posteriores.


4.- EJECUTAR clasificacion.ipynb
Este notebook realiza el preprocesado de los datos, entrena modelos (Regresión Logística, Random Forest Gradient Boosting, SVM) y evalúa (F1-score ponderado, Matriz de confusión, Curva ROC)


5.- EJECUTAR regresion.ipynb
Este notebook preprocesa los datos, entrena modelos (Regresión Lineal, Ridge, Lasso, Random Forest, Gradient Boosting) y evalúa (MAE, RMSE, R²)


6.- EJECUTAR unsupervised_learning.ipynb
Este notebook:
    -Aplica PCA para reducción de dimensionalidad
    -Aplica K-Means (k=3)
    -Analiza perfiles de estudiantes mediante visualización en espacio PCA y mapas de calor


7.- INFORME
El análisis completo, interpretación de resultados y conclusiones se encuentran en:
            informe_machine.pdf




Sofía Sánchez Guillán