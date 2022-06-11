FROM alpine:3.15
RUN apk add --no-cache php8-fpm
EXPOSE 9000
COPY ./www.conf /etc/php8/php-fpm.d
ENTRYPOINT ["php-fpm8","-F"]