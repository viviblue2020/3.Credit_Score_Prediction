<b>3.Credit_Score_Prediction (German Dataset) </b> 
<br> <br>
<b>1. Resumen:</b> <br> Exploración de los datos relacionados con el Riesgo Crediticio (Credit Score), entendimiento de la distribución de sus variables, patrones y finalmente planteamiento de varios modelos de predicción y selección del que presente mejor ajuste. 
Se exploraron modelos como Random Forest, XGBoost y Gaussian Naive Bayes. Dicho esto, se empleó el tercer modelo (GNB) como el definitivo para hacer las predicciones y su posterior implementación.
<br> <br>
<b>2. Contexto </b> <br>
El dataset original está compuesto por 1000 observaciones y 20 variables categóricas preparadas por el Dr. Hofman. Para algoritmos que requieren variables numéricas, Strathclyde University produjo el archivo "german.data-numeric". En este caso se analizará el dataset filtrado por Leonardo Ferreira. En este conjunto de datos, cada entrada representa a una persona que recibe un crédito de un banco. Cada persona se clasifica como riesgo crediticio bueno o malo según el conjunto de atributos. El enlace al conjunto de datos original se puede encontrar a continuación.
<br> <br>
<b>3. Contenido del dataset </b> <br>
Era casi imposible comprender el conjunto de datos original debido a su complicado sistema de categorías y símbolos. Por lo tanto, el autor de este dataset preparó un script de Python para convertirlo en un archivo CSV legible. Los atributos seleccionados son:
<br> <br>
1.Edad (numérica) <br>
2.Sexo (Categórica: masculino, femenino) <br>
3.Empleo (Numérica: 0 = no calificado y no residente, 1 = no calificado y residente, 2 = calificado, 3 = altamente calificado) <br>
4.Vivienda (Categórica: propio, alquilado o gratis) <br>
5.Cuentas de ahorro (Categórica: pequeño, moderado, bastante rico, rico) <br>
6.Cuenta corriente(Numérica, en DM - Marca Alemana) <br>
7.Monto del crédito (Numérica, in DM) <br>
8.Duración (Numérica, en meses) <br>
9.Propósito (Categórica: auto, muebles / equipo, radio / TV, electrodomésticos, reparaciones, educación, negocios, vacaciones / otros) <br>
10.Riesgo (Variable objetivo categórica: Riesgo bueno o malo) <br>
<br>
<b>Dataset</b> <br>
https://www.kaggle.com/kabure/predicting-credit-risk-model-pipeline/data?select=german_credit_data.csv

<b> Nota: Algunas gráficas construidas con la librería plotly, se pueden visualizar en Jupyter Notebook. Es algo que debo corregir para poder visualizarlas en esta plataforma (Github). </b>
