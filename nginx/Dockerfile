# FROM nginxproxy/nginx-proxy
# COPY vhost.d/default /etc/nginx/vhost.d/default
# COPY custom.conf /etc/nginx/conf.d/custom.conf

FROM nginx:1.25

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d