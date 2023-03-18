FROM nginx
RUN rm -rf usr/share/nginx/html/index.html
RUN rm -rf /etc/nginx/nginx.conf
COPY default.conf /etc/nginx/nginx.conf
COPY static /usr/share/nginx/html/