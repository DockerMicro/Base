FROM alpine:3.7

MAINTAINER Maciej Lisiewski <maciej.lisiewski@gmail.com>

RUN apk add --no-cache tini

ENTRYPOINT ["/sbin/tini", "--"]
