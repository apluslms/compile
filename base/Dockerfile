FROM --platform=$TARGETPLATFORM debian:bullseye-slim

ENV LANG=C.UTF-8

COPY rootfs /

RUN apt_install \
    apt-utils \
    ca-certificates \
    curl \
    gnupg dirmngr \
    git \
\
 && mkdir -p /work/

WORKDIR /work/
