FROM node:12.5.0-alpine

ENV HOME="/app" \
    LANG=C.UTF-8 \
    TZ=Europe/London

WORKDIR ${HOME}

RUN apk update && \
    apk upgrade && \
    npm install -g npm && \
    npm install -g @vue/cli

ENV HOST 0.0.0.0
EXPOSE 3000