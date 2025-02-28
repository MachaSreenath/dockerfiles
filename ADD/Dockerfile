FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf usr/share/nginx/html/index.html
ADD https://github.com/MachaSreenath/notes/01-crontab.git usr/share/nginx/html/index.html
CMD ["nginx","-g","daemon off;"]