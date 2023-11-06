From almalinux:8 
RUN yum install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ONBUILD ADD index.html /usr/share/nginx/html/index.html
# RUN echo "Hello this is first day of docker series" > /usr/share/nginx/html/hello.html
CMD [ "nginx", "-g","daemon off;"]