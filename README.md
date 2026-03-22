Módulo-8-SO3-CLI Comandos utilizados en Laboratorio Módulo 8 - Sistemas Operativos III
Este repositorio contiene los comandos prácticos con los cuales se desarrollaron las prácticas de el octavo laboratorio de la asignatura Sistemas Operativos III, impartida por el profesor Adrian Alcantara.
En el mismo se desarrollaron los siguientes temas:

Practica 1: Instalacion y configuracion de Docker
• Instalar Docker en mi servidor.
• Descargar una Imagen de NGINX web server (desde la Dockerhub).
• Crear un contenedor a partir la la imagen de NGINX en a que el puerto 8888 del host sera redireccionado al puerto 80 del contenedor de NGINX, de igual forma montar un volumen persistente /home/website --> /usr/share/nginx/html/.
• Crear una pagina HTML sencilla la cual tenga su nombre y matricula y nombrarla como index.html, una vez creada copiarla al la ruta del volumen persistente para que la misma puedea ser visualizada por el contenedor (/home/website).
• Ingrese al navegador (127.0.0.1:8888) y muestre la pagina que ha creado.

Practica 2: Instalacion de Portainer
• Descargar desde la Dockerhub una imagen de portainer.
• Crear a partir de la imagen, un contenedor y mapear todos los puertos internos del contenedor a los puertos externos del host.
• Ingresar a la interfaz de administracion de portainer (127.0.0.1:9443) y vincularla con el Docker Engine que se encuentra corriendo en el host local.
• Una vez se encuentre conectada, detener el contenedor de NGINX (de la practica previa) a travez de container, muestre el resultado en el navegador Web.

Practica 3: Despliegue de contenedor de Wordpress utilizando Docker-Compose
• Realize el proceso de instalacion de Docker-compose.
• Creen un archivo llamado docker-compose.yml donde se especifiquen las Variables de entorno que usaran los contenedores asi como un contenedor par ala BD y uno par ael aplicativo de wordpress.
• Realize el despliegue de los contenedores utilizando docker compose.
• Una vez finalizado el despliegue ingrese mediante el navegador y configure wordpress para su correcto uso.

Este es el enlace a la lista de reproduccion en youtube: ↓
https://www.youtube.com/playlist?list=PLpcZGYtY2vZZ7nBtnQbeLVhHIADBzg1Ds
