# Aplicación en Maven

## Configuración

Antes de empezar se procede a crear la siguiente estructura en el equipo local:

![m1](../imagenes/m1.png)

- Se crea dentro del directorio src/main/hello se crea el archivo HelloWorld.java con el siguiente contenido:

  ![q1](../imagenes/q1.png)

- Se crea el archivo Greeter.java dentro del directorio src/main/java/hello:

  ![q2](../imagenes/q2.png)

- A continuación, se procede a instalar maven y luego se ejecuta el comando export PATH=/opt/apache-maven-3.8.4/bin:$PATH y al final para probar la instalación se ejecuta el comando mvn -v:

  ![q3](../imagenes/q3.png)

  

## Definición de proyecto

Los proyectos hechos con maven se definen con un archico de tipo xml llamado pom.xml, para ello se procede a crear un archivo con el nombre pom.xml en la carpeta raiz del proyecto con el siguiente contenido:

![q4](../imagenes/q4.png)

## Construir código java

Maven está ahora listo para construir el proyecto.

Para probar la compilación se ejecuta el comando mvn compile:

![q5](../imagenes/q5.png)

- Se ejecuta el mvn package:

  ![q6](../imagenes/q6.png)

## Declarar dependencias

Si se quiere que además de decir “¡Hola Mundo!”,  se quiere que la aplicación imprima la fecha y hora actuales se debe cambiar el contenido del fichero HelloWorld.java:

![q7](../imagenes/q7.png)

A continuación, se añade dependencias al archivo pom.xml:

![q8](../imagenes/q8.png)

## Prueba

El primer paso es añadir JUnit como una dependencia a tu pom.xml, en el ámbito de la prueba, en la captura anterior se puede ver que se ha añadido.

Ahora se crea un caso de prueba en el directorio src/test/java/hello/GreeterTest.java como el siguiente:

![q9](../imagenes/q9.png)

Se añade tambien la independencia hamcrest al archivo pom.xml y se ejecuta el comando mvn test:

![q10](../imagenes/q10.png)

![q11](../imagenes/q11.png)



--------------------

------------------

--------------

