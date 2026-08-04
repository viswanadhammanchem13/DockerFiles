FROM almalinux:10
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://chatgpt.com/c/6a721d49-195c-83ee-85cd-9791d42f76e4 /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]