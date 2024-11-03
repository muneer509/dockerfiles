FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/muneer509/dockerfiles/refs/heads/main/docker_install.sh /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]