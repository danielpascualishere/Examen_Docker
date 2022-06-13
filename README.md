# Examen_Docker

Ejemplo 1

Ejecutamos el comando docker pull ubuntu:18.04 para descargar una imagen de forma previa. Seguidamente, creamos un contenedor de ubuntu:18.04 y creamos un acceso a un shell en él.


Ejemplo 2

Al crear el contenedor se ejecuta la orden ls / y posteriormente el contenedor pasa a estar parado. El acceso ya no estará disponible.


Ejemplo 3

Al ejecutar "docker run httpd" se crea un servidor Web Apache 2.4 en la ip mostrada y se nos muestra por pantalla el log de dicho servicio.


Ejemplo 4

Al ejecutar "docker run -it -w /etc debian:9 ls" el contenedor pasa a estar parado. Su acceso ya no estará disponible.


