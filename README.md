# Covid-19-PCA-CLUSTERING-RANDOM_FOREST

Se presenta un cuaderno de Jupyter que demuestra el funcionamiento de Estadistica Descriptiva para la implementacion de PCA, CLUSTERING y un un modelo de Machine Learning RANDOM FOREST
un análisis de PCA el cual nos permite realizar una reducción de dimensionalidad y obtener una cierta cantidad de componentes principales,
Para la aplicacion del Clustering se lo implementera con los componentes principales obtenidos previamente con el PCA  de igual manera se procede 
a realizar los K óptimos con los datos ya procesados.

1: Carga y procesamiento de los datos: Se realiza una limpieza, estandarización de los datos para Tener en formato Numérico.

2: Análisis de PCA: Se realiza un análisis de con una cierta cantidad de componentes.

3: Clustering: Se realiza un cluster con los componentes principales obtenidos para realizar una agrupacion de usuarios.

4: Random Forest : Se implementa un modelo de Machine Learning el cual nos dara un valor de cuales son las variables mas influyentes para el contagio de Covid-19.

# Estructura de los archivos.
- COVID19Notebook.ipynb : Contiene cada uno de los pasos realizados en nuestro metodo propuesto  para nuestro analisis Estadistico.
- COVID19NotebookHTML.html : Nuestro cuaderno de jupyter en formato html.
- DatasetPreprocesado.csv : Contiene nuestros datos ya procesados y estandarizados y poder tener unformacion totalmente numerica.



# Requisitos.
- Python 3.8
- Dataset: 2.COVID19_clasificacion [1]

# Librerias Necesarias.
- pandas
- numpy
- matplotlib
- OneHotEncoder
- StandardScaler
- LabelEncoder
- preprocessing
- train_test_split
- Pipeline

# Referencias
[1] 2.COVID19_clasificacion:https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/LQDFSE

[2] Machine Learning Approaches in COVID-19 Survival Analysis and Discharge Time Likelihood Prediction using Clinical Data. (2020, 4 julio). Recuperado de https://www.sciencedirect.com/science/article/pii/S2666389920300945

[3]Association between weather data and COVID-19 pandemic predicting mortality rate: Machine learning approaches. (2020, 1 septiembre). Recuperado de https://www.sciencedirect.com/science/article/pii/S0960077920305336#sec0003
