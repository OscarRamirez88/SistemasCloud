Pasos para ejecutar el archivo docker

1.- Una vez edscarguemos los archivos del proyecto (main.py & Dockerfile) abriremos una terminal en la carpeta en la que se encuentran almacenados los archivos

El archivo main.py contiene todo el codigo fuente y es el programa que se ejecutará, mientras que el archivo Dockerfile contiene las instrucciones necesarias para leer y montar la imagen de Docker

2.- Teendremos que ejecutar este comando para poder construir la imagen de Docker ( docker build -t prueba-crea . )

3.- Despues tendremos que colocar el comando para poder ejecutar la imagen de Docker el comando es ( docker run prueba-crea )

Una vez ejecutados estos comandos se tendra que ejecutar el codigo en este caso mostrando un mensaje de "Prueba de Docker"
