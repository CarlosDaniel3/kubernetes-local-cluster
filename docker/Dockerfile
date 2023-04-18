FROM nginx:1.9.8
RUN mkdir -p /var/www/html
ENV NGINX_CONF /etc/nginx/conf.d/default.conf
COPY ./nginx.conf $NGINX_CONF
COPY ./app /var/www/html/site/
EXPOSE 80
LABEL description="VIA CEP"
