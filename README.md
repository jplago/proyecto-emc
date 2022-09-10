# proyecto-emc
## Clasificación supervisada de pacientes con Trastorno de Déficit Atencional e Hiperactividad a partir de datos de resonancias magnéticas funcionales y datos fenotípicos.

En el notebook A - Matrices de conectividad.Rmd se construyen las matrices de conectividad de los sujetos a partir de las series de tiempo de sus resonancias magnéticas funcionales. 
Para el armado de las matrices de conectividad es necesario sustituir la carpeta /data por la misma carpeta del drive: https://drive.google.com/drive/folders/1f30V4aYJ7ic8_bGpbCmQp2MwLvZkfPLd?usp=sharing 

En el notebook B - Preprocesado.Rmd se realiza un preprocesado canónico a los datos y se generan dataframes globales para cada conjunto de datos.

Estos dos notebooks fueron desarrollados en el lenguaje R.

En el notebook C - SMOTE-EN-SVM Pipeline.ipynb se define el pipeline que constituye el modelo de clasificación, se optimizan hiperparámetros y se dan métricas en conjuntos de entrenamiento y test. Puede correrse con los datos incluidos en este repo.

Este notebook fue desarrollado en Python por conveniencia con el uso de la libreria -imblearn- para el manejo de SMOTE en el caso de uso requerido. 
