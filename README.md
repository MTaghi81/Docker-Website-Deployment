# Docker Website Deployment
This repository contains source code for a static website template.

The static website is deployed on a Linux server using Docker and Nginx.

Docker Deploy Commands
* git clone https://github.com/emestiza/Docker-Website-Deployment.git
* cd Docker-Website-Deployment
* vi Dockerfile
* cat Dockerfile

FROM nginx
COPY . /usr/share/nginx/html

* docker build -t websitedeploy .
* docker images
* docker run -itd -p 8085:80 59a8870d07e1

Use the DNS from the virtual machine running the Linux server to access the static website locally.
