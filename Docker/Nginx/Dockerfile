FROM nginx:latest
MAINTAINER Marrocamp <marrocamp@gmail.com>

RUN rm -f /etc/nginx/conf.d/*
COPY supervisord.conf /etc/supervisor/conf.d/

VOLUME ["/var/www", "/etc/nginx/conf.d"]
EXPOSE 80
