FROM node:lts-alpine

WORKDIR /usr/src/node

ADD main.js /usr/src/node/main.js

RUN npm init -y

RUN npm i express

CMD node main.js
