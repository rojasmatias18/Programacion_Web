\# Proyecto: Hoja de Vida con Docker y Nginx



\## Descripción

Este proyecto consiste en un sitio web estático desarrollado en HTML, desplegado en un contenedor Docker utilizando Nginx.



\## Estructura del proyecto



programacion\_web/

│

├── src/

│   └── index.html

├── Dockerfile

├── .dockerignore

└── README.md



\## Construir la imagen



docker build -t pmrojs0706/programacion-web:1.0 .



\## Ejecutar el contenedor



docker run -d -p 8080:80 pmrojs0706/programacion-web:1.0



\## Acceder al sitio



Abrir en el navegador:

http://localhost:8080



\## Imagen en Docker Hub



https://hub.docker.com/r/pmrojs0706/programacion-web



\## Descargar la imagen



docker pull pmrojs0706/programacion-web:1.0



\## Ejecutar la imagen descargada



docker run -d -p 8080:80 pmrojs0706/programacion-web:1.0

