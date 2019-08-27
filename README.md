## Universidad Distrital Francisco José de Caldas
## Facultad de Ingeniería
## Proyecto Curricular de Ingeniería de Sistemas

## Gestión Tecnológica

### Integrantes:

* Norbey Danilo Muñoz Cañón       20151020050
* Brayan Leonardo Sierra Forero   20151020059
* Camilo Enrique Rocha Calderón   20151020035

### Ejercicio de introducción a Docker haciendo uso de las herramientas Flask y MySQL

El presente proyeto de introducción a Docker consiste en una pequeña base de datos implementada en MySQL que establece conexión con el framework Flask, en una operación sencilla de CRUD. Esta implementación luego se trabaja junto a Docker, a modo de aplicación, con el fin de dar por entendido el funcionamiento y aplicabilidad dentro del proyecto codigo que despliega aplicaciones dentro de contenedores software.

### El contenido del proyecto desribe:

* app.py contiene la aplicación Flask que conecta con la base de datos

* init.sql es el script que define e inicializa la base de datos

* El Dockerfile contiene el conjunto de instrucciones que describen la imagen deseada y permiten la construcción automática

* requirements.txt contiene las dependencias necesarias ha ser instaladas. Estas se deben entregar a la imagen para ser incorporadas

* Por práctica, se ubica en un contenedor diferente la imagen de MySQL ha ser utilizada por la aplicación. Para ello se usa docker-compose con el fin de facilitar la orquestación entre los dos contenedores independientes. El archivo que define dicha tarea es docker-compose.yml

El proyecto se implemento ayudados en el tutorial de Shamir Stav: https://medium.com/@shamir.stav_83310/dockerizing-a-flask-mysql-app-with-docker-compose-c4f51d20b40d

