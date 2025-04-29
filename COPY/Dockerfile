FROM almalinux/9-base
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
COPY file.html /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]