FROM gliderlabs/alpine:latest
MAINTAINER Steven Brezina <steveinatorx@gmail.com>

RUN apk-install curl vim nginx

RUN mkdir -p /run/nginx
RUN mkdir -p /usr/share/data

EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
