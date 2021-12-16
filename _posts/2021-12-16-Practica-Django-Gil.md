typora-copy-images-to: ../imagenes
typora-root-url: ../



## Django



## Instalación

A continuación, se procede a instalar el Django en su propio contenedor. 

Para ello se sigue los siguientes pasos:

1.- Crea un directorio vacío con el nombre mi-django donde se alojará la imagen docker-compose.yml. El directorio se crea en documentos:

![m1](../imagenes/m1.png)



2.- Cambiar al directorio donde se alojará la imagen.

3.- Crear un archivo nuevo con el nombre  Dockerfile en el directorio creado con el contenido:

![m2](../imagenes/m2.png)



4.- Crear el archivo requirements.txt con el contenido:

![m3](../imagenes/m3.png)



5.- Se crea un archivo llamado docker-compose.yml que inicia el django con el siguiente contenido:

![m6](../imagenes/m6.png)



4.- Ahora se procede a ejecutar el archivo anterior con el comando  sudo docker-compose run web django-admin startproject composeexample :

![m9](../imagenes/m9.png)



5.- Se verifica el contenido del directorio:

![m10](../imagenes/m10.png)



6.- Editar el fichero composeexample/settings.py y modificarlo:

![m22](../imagenes/m22.png)



7.- Ejecutar el comando docker-compose up:

Al final me da un error:

![m33](../imagenes/m33.png)

---

---

