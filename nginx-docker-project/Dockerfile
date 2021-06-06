FROM nginx:latest
WORKDIR /home/cloud_user/nginxproject
RUN apt update -y && apt upgrade -y 
RUN rm -f /usr/share/nginx/html/index.html
VOLUME [ "/mnt/nginxproject" ]
ENV DEPLOYEDINFO="" 
