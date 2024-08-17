# **Análisis de un Dataset de ventas al detalle**
Este repositorio contiene un análisis de las transacciones de una empresa de comercio al por menor que vende principalmente productos únicos, cuyo fin es demostrar las competencias para el puesto de científico de datos en la empresa CITEC.

## **Requisitos**
Asegúrate de tener Python 3.11.12 o una versión superior instalada en tu sistema. Además, necesitarás instalar las siguientes librerías:

    pip install pandas matplotlib seaborn scikit-learn

## **Instrucciones para ejecutar el código**

1. Clona el repositorio

git clone https://github.com/apalacioj/Prueba-CITEC.git
cd Prueba-CITEC/

2. Instala las Dependencias: ejecuta el siguiente comando para instalar todas las dependencias necesarias. Alternativamente, puedes instalar manualmente las librerías indicadas en la sección de requisitos.

    pip install -r requirements.txt

3. Ejecuta el Notebook: abre el notebook en Jupyter o cualquier entorno de desarrollo compatible y ejecuta todas las celdas.

    jupyter notebook nombre_del_notebook.ipynb

## **Estructura**

- CITEC_test.ipynb: Notebook principal donde se lleva a cabo el análisis requerido.
- Online Retail.xlsx: Archivo que contiene el dataset utilizado.
- README.md: Este archivo que explica cómo configurar y ejecutar el proyecto.
- requirements.txt: Archivo que incluye todas las dependencias del proyecto.

## **Descripción del código**
El código sigue los siguientes pasos:

- Análisis exploratorio de datos: Los datos se cargan y se realiza una exploración inicial para entender su estructura. Se identifican patrones, valores atípicos, y posibles problemas de calidad en los datos.

- Limpieza de datos: Se aplican técnicas de limpieza de datos para manejar valores faltantes, duplicados y errores en el dataset. Además, se eliminan los valores atípicos.

- Análisis de cohortes: Se realiza un análisis de cohortes para entender el comportamiento de los clientes a lo largo del tiempo, considerando la fecha y el país de la primera compra realizada.

- Construcción del modelo predictivo: Se entrena un modelo de regresión logística para predecir la probabilidad de que un cliente realice una nueva compra a los 30 días.

- Evaluación del modelo: Se generan métricas de evaluación como la matriz de confusión, el ROC AUC score y reportes de clasificación.

- Visualización de resultados: Se visualizan las probabilidades predichas con gráficos para interpretar mejor los resultados. Además, a lo largo del código se muestran otros gráficos para apoyar los resultados.

## **Contacto**
Si tienes preguntas o necesitas asistencia adicional, puedes contactarme a través de apalacioj@eafit.edu.co.
