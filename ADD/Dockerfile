FROM almalinux:10
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://stackoverflow.com/questions/24241292/dockerized-nginx-is-not-starting  /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]