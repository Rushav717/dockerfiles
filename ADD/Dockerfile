FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/DAWS-82S/notes/refs/heads/main/session-01.txt /usr/share/nginx/html/index.html
CMD [ "nginx", "-g", "daemon off;" ]