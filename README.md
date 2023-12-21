# Predictor_Dias_Pago

# Descripción del Proyecto
Este proyecto fue elaborado con el objetivo de construir y evaluar modelos de regresión basados en redes neuronales para predecir la variable objetivo "DiasCalle_h", es decir, los dias que se tardará en cobrar las facturas de cada cliente. Se ha utilizado un conjunto de datos del archivo "Data_calle_score.csv" para entrenar y evaluar el rendimiento del modelo.

# Estructura del Proyecto
El proyecto consta de los siguientes elementos:

# Scripts de Análisis y Modelado:

Script_1_Analisis_Exploratorio.py: Este script realiza un análisis exploratorio de los datos, visualiza la distribución de la variable objetivo "DiasCalle_h" y realiza la exploración de otras variables relevantes.

Script_2_Modelado_DataCalle.py: Este script realiza el preprocesamiento de los datos, define un modelo de regresión basado en redes neuronales utilizando MLPRegressor, y realiza una búsqueda de hiperparámetros mediante validación cruzada.

# Resultados:
Se generan archivos de resultados, como el archivo "data_calle_pred.csv", que contiene las predicciones del modelo para el conjunto de datos.


# Requisitos del Sistema

Asegúrate de tener las siguientes bibliotecas instaladas antes de ejecutar los scripts:
pip install numpy pandas matplotlib seaborn scikit-learn

# Instrucciones de Ejecución

Descarga de Datos:
Asegúrate de tener el archivo de datos "Data_calle_score.csv" en la ruta especificada en el script.

Ejecución de Scripts:
Ejecuta los scripts en el orden mencionado para realizar el análisis exploratorio y el modelado.

Resultados:
Revisa los archivos de resultados generados, como "data_calle_pred.csv", para obtener las predicciones del modelo.

# Configuración del Entorno
Se recomienda utilizar un entorno de Python con las versiones de bibliotecas especificadas en los scripts para garantizar la reproducibilidad.

# Notas Adicionales
Puedes ajustar los parámetros del modelo y la configuración de la búsqueda de hiperparámetros según tus necesidades en el script de modelado.
