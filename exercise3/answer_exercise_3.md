# Exercise 3

He creado un Dockerfile usando la imagen de NGINX 1.19.3
He puesto esta instrucción "COPY ./static_content/index.html /usr/share/nginx/html/index.html", para copiar mi index.html ubicado en la carpeta static_content y reemplazar el html por defecto del server web NGINX.

He corrido esta orden "docker build -t exercise3 ." desde este directorio para construir la imagen a partir del Dockerfile.

Luego he ejecutado esta orden "docker run -p 8081:80 exercise3" para crear el contenedor a partir de la imagen exercise3 y ejecutarlo en el 8081 de mi máquina, y 80 de NGINX.
Al acceder a la URL localhost:8081/index.html vemos que se ejecuta correctamente y hay un h1 que pone HOMEWORK 1

Como ya tenia en otro contenedor el puerto 8080 corriendo he usado el 8081.
