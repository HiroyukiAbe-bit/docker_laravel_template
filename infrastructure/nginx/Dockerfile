FROM nginx:1.25.1-alpine

ENV TZ=UTC

# nginx config file
COPY ./infrastructure/nginx/*.conf /etc/nginx/conf.d/

WORKDIR /var/www/html