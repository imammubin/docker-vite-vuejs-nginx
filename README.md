Build docker image from VITE VUEJS project and NGINX as dist build

====================================
Run Docker Compose
or
Build The Image
====================================

*Run Docker Compose

docker compose up

====================================

*Build The Image From Dockerfile
1. docker build -t docker-vite-vuejs-nginx .

then, running the image
1. docker run -it -p 8080:80 docker-vite-vuejs-nginx sh
2. type command to run nginx
    nginx -g 'daemon off;'

====================================

*Note 
for a sample, try this:
1. docker run -it -p 8080:80 imammubin/docker-vite-vuejs-nginx-dist nginx -g 'daemon off;'