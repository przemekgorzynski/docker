FROM ubuntu
RUN apt-get update
RUN apt-get install -y nginx
EXPOSE 80
COPY index.nginx-debian.html /var/www/html
CMD ["nginx", "-g", "daemon off;"]
