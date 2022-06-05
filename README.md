# Biomarcadores para imagen médica: Clasificación automática de fracturas de radio distal

Trabajo de Final de Máster, Universidad Oberta de Catalunya, Máster en Ciencia de Datos


Author: Álvaro Díaz Sánchez 

Supervisor: Héctor Espinós Morató

El objetivo de este TFM es el desarrollo de una arquitectura de redes paralelas (CNN) para clasificación autómatica de fracturas de radio distal, aprovechando una red preentrenada VGG-19.

Los siguientes scripts han sido generados para el desarrollo de la metodologia propuesta en la memoria:

* resize_splitData.ipynb : Realiza el redimensionamiento y separa los datos en el train data y test data
* model_training.ipynb : Script que entrena los diferentes modelos de redes paralelas para todos los hiperparámetros
* eval_model.ipynb : Script adicional que permite obtener las métricas de evaluación de un modelo entrenado, el saliency map de una imagen concreta o una imagen erronea de un modelo entrenado


En la carpeta Data se encuentra un ejemplo de un modelo guardado y una imagen de muestra.

 

