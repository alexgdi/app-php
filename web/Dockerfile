FROM alpine:3.15
RUN apk add --no-cache nginx && mkdir -p /run/nginx && rm -rf /etc/nginx/http.d/default.conf
COPY ./example.com.conf /etc/nginx/http.d
CMD ["nginx", "-g", "daemon off;"]
