FROM almalinux:10
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/viswanadhammanchem13/DockerFiles/refs/heads/main/CMD/Dockerfile  /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD Sample-1.tar /tmp/
CMD ["nginx", "-g", "daemon off;"]