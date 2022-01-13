## Rails

## Instalación

- Crear un archivo nuevo con el nombre  Dockerfile en el directorio creado con el contenido:

  ![ra1](/home/gilrs/Documentos/repo/gilrustom.github.io/imagenes/ra1.png)

- Crear el archivo Gemfile con el contenido:

  ![ra2](../imagenes/ra2.png)

- Se crea un archivo vacio Gemfile.lock para construir nuestro Dockerfile:

  ![ra3](../imagenes/ra3.png)

- Se crea el archivo entrypoint.sh para solucionar un problema específico de Rails que impide que el servidor se reinicie cuando un determinado archivo server.pid ya existe. Este script se ejecutará cada vez que se inicie el contenedor:

  ![ra4](../imagenes/ra4.png)

- Al final se crea un archivo llamado docker-compose.yml que inicia el Rails con el siguiente contenido:

  ![ra5](../imagenes/ra5.png)

- Ahora se procede a ejecutar el archivo anterior con el comando  sudo  docker-compose run --no-deps web rails new . --force --database=postgresql :


![ra6](../imagenes/ra6.png)

- Se verifica el contenido del directorio:

  ![ra7](../imagenes/ra7.png)

- En el archivo database.yml introducir los siguientes cambios:

  ![ra8](../imagenes/ra8.png)

- Se bootea la app con el comando: docker-compose up:

  ![ra9](../imagenes/ra9.png)

- Al final:

![ra10](../imagenes/ra10.png)



---------------------------------------------------------------------------------------------------------------------------------------------------------

