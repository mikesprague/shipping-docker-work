FROM node:7.2

MAINTAINER Mike Sprague

RUN apt-get update \
    && apt-get install -y apt-utils \
    && apt-get install -y curl zip unzip git \
    && apt-get -y autoremove \
    && apt-get clean \
    && rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*
