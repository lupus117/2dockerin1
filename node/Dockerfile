FROM node:lts-alpine

EXPOSE 8000

WORKDIR /usr/src/node

ADD main.js /usr/src/node/main.js

RUN npm init -y

RUN npm i express

CMD node main.js
