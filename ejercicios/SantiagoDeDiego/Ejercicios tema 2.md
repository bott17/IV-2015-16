#Ejercicio 1

Yo he escogido para instalar npm por su facilidad de instalación en MAC. Solo tenemos que instalar el archivo que encontramos en la [Página oficial](https://nodejs.org/en/) y darle a siguiente, siguiente al estilo windows.

Además también nos instala la última versión de node.js, podemos verlo escribiendo `node -v` y nos devuelve la versión que hemos instalado, en mi caso la 4.2.1

También instalaremos el módulo express, un framework que nos permitirá desarrollar aplicaciones web. Esto lo hacemos mediante el comando `sudo npm install -g express-generator`

##Instalación de virtualenv en MAC OSX
Primero de todo instalamos el gestor de paquetes pip. Esto además nos servirá para el siguiente ejercicio en el que instalaremos Django. Para ello escribimos `sudo easy_install pip` . Una vez instalado, ya solo tenemos que escribir `sudo pip install virtualenv` y ya tenemos instalado virtualenv en Mac.

El motivo de esta instalación es que utilizo bastante el mac para programar en python y me parecía interesante tener un entorno de python.

#Ejercicio 2

Ahora vamos a crear una aplicación web sencilla sobre la que poder trabajar. En mi caso voy a hacerla con node.js y su módulo express, de ahí que lo instalase anteriormente. En mi caso voy a crearla en mi carpeta de la asignatura, así que vamos a nuestra carpeta y escribimos el comando: `express primera_app_nodejs`. Una vez hecho esto instalamos las dependencias con `cd primera_app_nodejs && npm install`. Esto instalará las librerías (módulos) y las dependencias de estas, necesarias para correr nuestro proyecto. Ya con esto tenemos lo necesario para empezar a programar nuestra primera aplicación web.

Para ver que funciona la ejecutamos escribiendo: `DEBUG=primera_app_nodejs:* npm start` como pone en la terminal que lo hagamos. Ahora en la dirección local con el puerto 300 encontramos:

![Express](http://i864.photobucket.com/albums/ab201/Santiago_de_Diego/Express%20funcionando_zpsqrzyaexb.png)
