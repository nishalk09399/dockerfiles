From almalinux:8 
#almalinux is same as centOS
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
RUN echo "Hello this is first day of docker series" > /usr/share/nginx/html/index.html
#damon off command takes our container running and attach to screen
ENTRYPOINT [ "nginx", "-g","daemon off;"]