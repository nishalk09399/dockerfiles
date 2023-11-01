From almalinux:8 
#almalinux is same as centOS
RUN yum install nginx -y
RUN echo "Hello this is first day of docker series" > /usr/share/nginx/html/hello.html
#damon off command takes our container running and attach to screen
CMD [ "nginx", "-g","daemon off;"]