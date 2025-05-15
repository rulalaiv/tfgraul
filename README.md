Docker Compose File con todo el setup de contenedores docker-compose.yaml
Certificados SSL autofirmados nginx.crt y nginx.key 
Configuración Nginx Reverse Proxy app.conf

Idea del proyecto: Entorno colaborativo con contenedores Docker. 3 contenedores idénticos con una web en la que cambia el fondo de color en cada uno. 
Además Nextcloud y Collabora, Nextcloud es una nube donde almacenar archivos y documentos, Collabora permite la edición de los documentos.

https:tfgraul  | https:tfgraul/hola1  | https:tfgraul/hola2  | https:tfgraul/nextcloud | https:tfgraul/collabora

Problema: https:tfgraul/nextcloud no funcinona correctamente, accedes al dominio y muestra un mensaje: Nextcloud y un link a su web, en lugar de la 
web donde poder hacer el registro y donde poder usar Nextcloud. 
Lo que sospecho es que fallará algo de la configuración de Nginx, pero he probado mil cosas y ni idea.

######################################################################################################################################################################################

Docker Compose File with all container setup docker-compose.yaml Self-signed SSL certificates nginx.crt and nginx.key Configuration Nginx Reverse Proxy app.conf

Project idea: Collaborative environment with Docker containers. 3 identical containers with a web where the background colour changes in each one. 
In addition Nextcloud and Collabora, Nextcloud is a cloud where to store files and documents, Collabora allows the edition of the documents.

https:tfgraul | https:tfgraul/hola1 | https:tfgraul/hola2 | https:tfgraul/nextcloud | https:tfgraul/collabora

Problem: https:tfgraul/nextcloud does not work correctly, you access the domain and it shows a message: Nextcloud and a link to its website, instead of the website 
where you can register and where you can use Nextcloud. 
What I suspect is that something is wrong with the Nginx configuration, but I've tried a thousand things and I have no idea.

