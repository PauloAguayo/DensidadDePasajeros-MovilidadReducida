# DensidadDePasajeros-MovilidadReducida
El presente trabajo estudia el efecto de la densidad de pasajeros en el espacio ocupado por personas con movilidad reducida.

En esta entrega, se utilizó el poder de las redes neuronales, más específicamente de Deep Learning, en el que se usó la red Faster RCNN con el modelo InceptionV2. La red fue entrenada con imágenes de los experimentos ejecutados en el Laboratorio de Dinámica Humana de la Universidad de Los Andes (Chile), MobilityAids Dataset (Autonome Intelligente Systeme, Albert-Ludwigs-Universität Freiburg - http://mobility-aids.informatik.uni-freiburg.de/), Head and Shoulder Detection using Convolutional Networks and RGBD data (http://www.site.uottawa.ca/research/viva/projects/head_shoulder_detection/index.html) y del canal de Youtube UWSpinalCordInjury.
La red fue entrenada a través de Google Cloud Platform con una tarjeta GPU Tesla T4, con una duración de aproximadamente 7-8 horas. Esta red está encargada de detectar cabezas y personas en sillas de ruedas.


# Instalación
