# Diplomado PUCP - Detección en tiempo real de personas con mascarilla en ambientes no controlados

Proyecto Final de fin de curso de Vision Artificial del Diplomado de Inteligencia Artificial de la PUCP.

# Presentacion

El proyecto permite al usuario realizar la deteccion rostros y el reconocimiento de mascarillas en una imagen o video 

# Integrantes

- CRUZADO PADILLA, CARLOS ANTONIO
- GARCÍA RIVAS PLATA, CECILIA EDITH
- GAMARRA MORENO, ABRAHAM ESTEBAN

# Pre-Requisito

El proyecto ha sido ejecutado en Colab.
Requiere de Multi-task Cascaded Convolutional Networks (MTCNN) para el proceso de deteccion de rostros requiere del siguiente comando para la instalacion.

  !pip install mtcnn

# Proceso de ejecucion

- Leer una imagen o un video
- Aplicamos MTCNN (Multi-Task Cascaded Convolutional Neural Network) para detectar rostros en la imagen o video 
- Aplicamos un modelo en Pytorch entrenado desde Resnet con Transfer Learning para verificar mascarillas
- Clasifica con un cuadro verde o rojo, según si el rostro tiene mascarilla  o no
- Repetir el proceso para las siguientes imágenes
