FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#Source dest should be in current directory only
COPY index.html /usr/share/nginx/html/index.html   
CMD ["nginx","-g","daemon off;"]