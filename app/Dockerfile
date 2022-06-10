FROM alpine:3.15
RUN apk add --no-cache php8-fpm
EXPOSE 9000
COPY index.php /var/www/
CMD ["php-fpm8"]