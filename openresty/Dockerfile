FROM openresty/openresty:centos

RUN chmod -R 775 /var/run/openresty/

COPY nginx.conf /usr/local/openresty/nginx/conf/nginx.conf
COPY nginx.vh.default.conf /etc/nginx/conf.d/default.conf

EXPOSE 8080
