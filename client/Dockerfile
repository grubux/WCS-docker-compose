# Dockerfile
FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app

COPY package*.json ./
RUN npm install

COPY public public
COPY src src
COPY src src

ENV WDS_SOCKET_PORT 0

CMD npm start