FROM almalinux
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD sample-1.tar /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;" ]