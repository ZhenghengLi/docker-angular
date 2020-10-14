FROM node:12-slim

ARG SOURCE_DIR=/opt/angular-devel

ADD $PWD $SOURCE_DIR

RUN set -x \
    && cd $SOURCE_DIR \
    && npm install \
    && rm package*.json
