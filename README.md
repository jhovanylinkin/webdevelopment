# Programación web Agosto - diciembre 2017 S8A
## Notas
* existe un archivo llamado host donde se almacena la resolucion de nombres de manera local. se ecuentra en la
carpeta `/etc/hosts`
* **Hosting:**
  * **URL:** http://kindred.byethost9.com
  * **Cpanel URL:** http://cpanel.byethost9.com
  * **Username:**   b9_20576883
  * **Password:**   8jqdw07p
  * **FTP Username:**  b9_20576883
  * **FTP Password:**  8jqdw07p
  * **FTP HostName:**  ftp.byethost9.com
  * **MySQL Host Name:** sql307.byethost9.com
  * **MySQL Password:** 8jqdw07p
  * **MySQL UserName:**  b9_20576883


## Configurar xampp en ubuntu
  * Damos permisos para poder modificar el directorio `/opt/htdocs`, con el comando:
  `sudo chmod a+w /opt/lampp/htdocs`
  * Creamos un enlace simbólico entre el directorio y una ubicación en nuestra carpeta personal, por ejemplo: **/home/usuario/Webs**, para de esta forma tener nuestros proyectos en la carpeta personal, con el comando:
  ```sudo ln -s /opt/lampp/htdocs /home/usuario/Webs```
  **Nota:** donde pone “usuario” se ha de poner nuestro nombre de usuario.

### Habilitar [xampp server](https://www.apachefriends.org/es/index.html)
* Para iniciar `$ sudo /opt/lampp/lampp start`

* Para detener `$ sudo /opt/lampp/lampp stop`

* Para reiniciar `$ sudo /opt/lampp/lampp restart`

* Para desarrollar aplicaciones, debemos de realizar siempre el anterior paso para arrancar Xampp, pero existe una gui (interfaz gráfica que permite arrancar de forma fácil todos los servicios o uno por uno. Es el llamado Panel de Control de Xampp y se abre con el siguiente comando:
`sudo/opt/lampp/share/xampp-control-panel/xampp-control-panel`

* **Sí ocurre un error al tratar de ejecutar la interfaz grafica de xampp-control-panel. Ejecuta el siguiente comando:** `sudo apt-get install python-glade2`
