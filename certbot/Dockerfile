FROM alpine:latest
MAINTAINER David Yip <yipdw@member.fsf.org>

RUN apk add --no-cache certbot

EXPOSE 80
EXPOSE 443

VOLUME /etc/letsencrypt
VOLUME /var/lib/letsencrypt
