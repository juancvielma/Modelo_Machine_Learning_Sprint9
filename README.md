# Modelo_Machine_Learning_Sprint9# Modelo Machine Learning Sprint9

Este proyecto forma parte del Sprint 9 de Machine Learning y tiene como objetivo analizar el comportamiento mensual de los usuarios. Se utiliza un dataset que contiene información sobre llamadas, minutos, mensajes y tráfico de Internet, y se clasifica a los usuarios según su plan (Ultra o Smart).

## Contenido del Proyecto

- **Modelo.ipynb**: Notebook de Jupyter que incluye:
  - Carga y exploración del dataset.
  - División del dataset en conjuntos de entrenamiento, validación y prueba.
  - Entrenamiento y ajuste de hiperparámetros de modelos (por ejemplo, Random Forest).
  - Evaluación del modelo y realización de una prueba de cordura.
- **/datasets/users_behavior.csv**: Dataset con la información del comportamiento de los usuarios.

## Datos del Proyecto

El dataset `users_behavior.csv` contiene la siguiente información para cada usuario:

- **calls**: Número de llamadas.
- **minutes**: Duración total de las llamadas en minutos.
- **messages**: Número de mensajes de texto.
- **mb_used**: Tráfico de Internet utilizado en MB.
- **is_ultra**: Plan del mes actual (1 para Ultra, 0 para Smart).

## Requisitos

- **Python 3.x**
- **Jupyter Notebook**
- Librerías:
  - pandas
  - numpy
  - matplotlib
  - scikit-learn

Para instalar las dependencias, puedes usar:

```bash
pip install pandas numpy matplotlib scikit-learn
