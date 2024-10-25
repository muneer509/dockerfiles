#CMD instruction will run at the time of conatiner running,
# It will keep container running continuesly, like systemctl in linux VM
# docker build is image creation
# Docker run is container creation, so CMD will excute at the time of container creation which means it will excute at docker run not at the time of docker build
FROM almalinux:9
RUN dnf install nginx -y
CMD ["nginx" "-g" "daemon off;" ]