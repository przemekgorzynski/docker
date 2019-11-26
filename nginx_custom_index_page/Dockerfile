FROM ubuntu
RUN apt-get update
RUN apt-get install -y nginx
COPY index.nginx-debian.html /var/www/html
CMD nginx -g 'deamon off;'                 #default container command - commands that starts when image runs - always PID 1
