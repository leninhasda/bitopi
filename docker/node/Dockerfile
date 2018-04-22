FROM node:alpine

LABEL maintainer="Lenin Hasda"

WORKDIR /var/www/html

ARG uid=999

RUN apt-get update \
    && apt-get install -y git \
    && apt-get -y autoremove \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*

RUN usermod -u $uid node
