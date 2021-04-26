FROM ubuntu:14.04
MAINTAINER Jerry "huyaoban@163.com"
ENV REFRESHED_AT 2020-02-15
RUN apt-get update
RUN apt-get -y -q install nginx
RUN mkdir -p /var/www/html
ADD nginx/global.conf /etc/nginx/conf.d/
ADD nginx/nginx.conf /etc/nginx/nginx.conf
EXPOSE 80
