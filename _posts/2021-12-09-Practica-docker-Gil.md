typora-copy-images-to: ../imagenes
typora-root-url: ../



## DOCKER

En está práctica se va a crear un primer contenedor y posteriormente ejecutarlo.



## Primer Contenedor

Para ello se va a utilizar un repositorio de GitHub que ya contiene los componentes contenedorizados: https://github.com/victorponz/docker/tree/master/P1.

Antes de empezar se procede a comprobar si Docker ya esta instalado en el equipo, para ello se ejecuta el comando docker ps:

![v1](../imagenes/v1.png)

Una vez ya se sabe como funciona el Dockerfile, se necesita ejecutar los siguientes archivos:

![v2](../imagenes/v2.png)

![v4](../imagenes/v4.png)

Una vez lanzado el debug.sh, se visita la página varias veces y se verá que el contenedor de visitas aumenta:

![v5](../imagenes/v5.png)

Cabe mensionar que en el archivo debug.sh se ha cambiado un ajuste  de puertos que es 8086:80 en lugar de 8086:80 

![v7](../imagenes/v7.png)





---

