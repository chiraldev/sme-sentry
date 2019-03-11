FROM nginx:stable as nginx
RUN rm -rf /etc/nginx/conf.d/*
COPY ~/qa/nginx/conf.d/default.conf /etc/nginx/conf.d/
COPY ~/qa/nginx/certs/* /etc/nginx/ssl/

