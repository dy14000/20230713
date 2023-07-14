FROM ubuntu:focal
ENV DEBIAN_FRONTEND=noninteractive

#
RUN apt-get update \
    && docker pull nginx
RUN mkdir web-service_nginx
ADD sample4 /web-service_nginx
ADD sample4/* /var/www/html/


#포트노출
CMD bin/bash echo "hi my name is dayoung"
CMD ["nginx", "-g", "daemon off;"]
EXPOSE 80