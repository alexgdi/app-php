FROM alpine:3.15
RUN apk add --no-cache nginx && mkdir -p /run/nginx
EXPOSE 80
#EXPOSE 443
CMD ["nginx", "-g", "daemon off;"]
