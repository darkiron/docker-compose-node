FROM node:alpine

RUN apk add --no-cache --virtual .gyp python make g++ \
    && npm install -g serve \
    && apk del .gyp

CMD ["node","index.html"]