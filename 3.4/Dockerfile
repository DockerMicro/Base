FROM alpine:3.4

MAINTAINER Maciej Lisiewski <maciej.lisiewski@gmail.com>

RUN apk add --no-cache tini

ENTRYPOINT ["/usr/bin/tini", "--"]