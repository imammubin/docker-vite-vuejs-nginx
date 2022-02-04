Build docker image from VITE VUEJS project and NGINX as dist build

Build The Image
1. docker build -t docker-vite-vuejs-nginx .

Running the image
1. docker run -it -p 8080:80 docker-vite-vuejs-nginx nginx -g 'daemon off;'