FROM bhuisgen/alpine-backup:latest
LABEL maintainer="Boris HUISGEN <bhuisgen@hbis.fr>"

RUN apk add --update mariadb-client && \
    rm -rf /var/cache/apk/*

COPY rootfs/ /
