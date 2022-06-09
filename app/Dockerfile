FROM alpine:3.15
RUN apk add --no-cache php8-fpm
EXPOSE 9000
WORKDIR /var/www
COPY ./www /var/www/
CMD ["php-fpm"]
