FROM almalinux:9 
RUN mkdir /tmp/workdir-demo
# Here cd command will not work and hence we are going to use WORKDIR 
# RUN cd /tmp/workdir-demo
WORKDIR /tmp/workdir-demo
RUN pwd 
RUN echo "Hello I am in work directory" > hello.txt
CMD [ "sleep","1000" ]
