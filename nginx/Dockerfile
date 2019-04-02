FROM ubuntu
MAINTAINER nitish
RUN apt-get update
RUN apt-get install -y nginx \
    vim \
    net-tools
EXPOSE 80
CMD ["nginx","-g","daemon off;"]
