# Ejercicio 1 - Servidor de base de datos

- Arrancar un contenedor que se llame `bbdd` y  que ejecute una instancia de la imagen mariadb para que sea accesible desde el puerto 3306.

- Antes de arrancarlo visitar la página del contenedor en [Docker Hub](https://hub.docker.com/) y establecer las variables de entorno necesarias para que:
    - La contraseña de root sea `root`.

    - Crear una base de datos automáticamente al arrancar que se llame `prueba`.

    - Crear el usuario `invitado` con la contraseña `invitado`.

Entregar un documento con las siguientes capturas de pantalla y los comandos empleados para resolver cada apartado:

- Captura de pantalla y documento que desde el navegador muestre el fichero `index.html`.

- Captura de pantalla y documento que desde un navegador muestre la salida del script `mes.php`.

- Captura de pantalla y documento donde se vea el tamaño del contenedor `web` después de crear los dos ficheros.

- Captura de pantalla y documento donde desde un cliente de base de datos (instalado en tu ordenador) se pueda observar que hemos podido conectarnos al servidor de base de datos con el usuario creado y que se ha creado la base de datos prueba (`show databases`). El acceso se debe realizar desde el ordenador que tenéis instalado docker, no hay que acceder desde dentro del contenedor, es decir, no usar `docker exec`.

- Captura de pantalla y documento donde se comprueba que no se puede borrar la imagen mariadb mientras el contenedor `bbdd` está creado.