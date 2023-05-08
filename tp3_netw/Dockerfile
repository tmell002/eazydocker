FROM ubuntu:18.04

MAINTAINER "mellah.taoufik@gmail.com"

RUN apt-get update -y

RUN apt-get install -y git nginx iputils-ping

RUN rm -rf /var/www/html/*

RUN git clone https://github.com/diranetafen/static-website-example.git /var/www/html/

EXPOSE 80

ENTRYPOINT ["nginx", "-g", "daemon off";]
