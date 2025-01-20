# Predicción de Precios de Laptops con Machine Learning

Este proyecto utiliza técnicas de Machine, para predecir el precio de laptops basándose en sus características técnicas.

## ¿De qué se trata?

En el mundo actual, la elección de una laptop puede ser abrumadora debido a la gran cantidad de modelos y especificaciones disponibles.
El proyecto busca simplificar este proceso al proporcionar una herramienta que estima el precio de una laptop basándose en sus características clave, como la cantidad de RAM, el tamaño de la pantalla, el tipo de procesador, entre otras.

## ¿Cómo funciona?

El proyecto sigue un flujo de trabajo típico de Machine Learning:

1.  **Recopilación y Limpieza de Datos:** Se recopilaron datos de kanggle (https://www.kaggle.com/datasets/muhammetvarl/laptop-price/) Se realizó una normalizacion de datos para asegurar la calidad de los datos.

2.  **Análisis Exploratorio de Datos (EDA):** Se exploraron los datos para entender las relaciones entre las características de las laptops y sus precios, tambien se utilizaron visualizaciones como histogramas y diagramas de dispersión, se aplicó una transformación logarítmica al precio para mejorar el modelado.

3.  **Preprocesamiento de Datos:** Se transformaron las variables categóricas (como la marca de la laptop) a numéricas para que pudieran ser utilizadas por el modelo.

4.  **Modelado:** Se entrenaron direntes modelo pero el mejor modelo fue Random Forest para predecir el precio de las laptops. 

5.  **Evaluación:** Se evaluó el rendimiento del modelo utilizando métricas como el R² (coeficiente de determinación), que alcanzó un valor de aproximadamente 0.78 en la escala logarítmica del precio.

## ¿Qué tecnologías se utilizaron?

*   **Python:** El lenguaje de programación principal.
*   **Pandas:** Para el manejo y análisis de datos.
*   **NumPy:** Para cálculos numéricos.
*   **Scikit-learn:** Para el modelado de Machine Learning (Random Forest, preprocesamiento, etc.).
*   **Statsmodels:** Para análisis estadístico (regresión lineal).
*   **Matplotlib y Seaborn:** Para la visualización de datos.
*   **Joblib:** Para guardar y cargar el modelo entrenado.
