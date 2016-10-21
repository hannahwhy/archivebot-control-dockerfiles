FROM alpine:latest
MAINTAINER David Yip <yipdw@member.fsf.org>

RUN apk add --no-cache openssh
RUN adduser -h /home/archivebot -s /sbin/nologin -u 500 archivebot -D
RUN passwd -u archivebot

VOLUME /home/archivebot/.ssh
VOLUME /etc/ssh
