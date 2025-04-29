FROM almalinux/9-base
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://www.docker.com/blog/docker-best-practices-understanding-the-differences-between-add-and-copy-instructions-in-dockerfiles/ /usr/share/nginx/html/index.htm
CMD [ "nginx", "-g", "daemon off;" ]