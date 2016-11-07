FROM gliderlabs/alpine:latest
MAINTAINER Steven Brezina <steveinatorx@gmail.com>

#ENV TERM xterm
RUN apk-install curl vim nginx

RUN mkdir -p /run/nginx

EXPOSE 80
#ENTRYPOINT ["/bin/bash"]
CMD ["nginx", "-g", "daemon off;"]
