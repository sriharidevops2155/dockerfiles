FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#Source dest should be in current directory only
ADD https://raw.githubusercontent.com/sriharidevops2155/terraform/refs/heads/main/state/ec2.tf    /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
RUN sample-1.tar /tmp
CMD ["nginx","-g","daemon off;"]