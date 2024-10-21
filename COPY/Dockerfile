FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN hello.html /usr/share/nginx/html/hello.html
CMD ["nginx", "-g", "daemon off;"]