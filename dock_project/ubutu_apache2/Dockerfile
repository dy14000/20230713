FROM ubuntu:focal
ENV DEBIAN_FRONTEND=noninteractive

#
RUN apt-get update
    && apt-get install -y
CMD chmod



RUN mkdir web-service_apache2
ADD sample1 /web-service_apache2

#포트 노출
EXPOSE 80
CMD ["apache2ctl", "-D","FROEGROUND"]