FROM almalinux:8
RUN  yum install nginx -y      
COPY index.html /usr/share/nginx/html/index.html
ADD https://github.com/satish-sunkara01/dockerfiles/blob/main/LABELS/Dockerfile /tmp/
ADD dwsample1-tar.tar /tmp/
CMD [ "nginx", "-g", "daemon off;" ]