FROM almalinux:8
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY image /usr/share/nginx/html/
CMD ["nginx","-g","daemon off;"]