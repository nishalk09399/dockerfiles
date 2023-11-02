From nginx

#bydefault index.html we are removing here and replacing our html file instead
RUN rm -rf /usr/share/nginx/html/index.html

#files should be available in current directory where dockerfile exist
COPY index.html /usr/share/nginx/html/index.html

