# podman-lamp


# mysql env values
MYSQL_USER="admin"
MYSQL_PASSWORD="redhat"
MYSQL_ROOT_PASSWORD="redhat"
MYSQL_DATABASE="sampledb"


Despues de crear el siguiente pod con el proyecto de git, para conectar el myqsl con el php se tienen que añadir las variables de entorno como configmap y el nombre de la bd como un nombre general

<br>
- database-name -> value mysql -> database-user

<br>
El nombre de las variables de entorno pueden cambiar dependiendo del nombre del servicio de la bd, checar con el comando de `env` en el contenedor 
