# Dockerfile
FROM node:lts-alpine

RUN mkdir /app
WORKDIR /app

COPY package*.json ./
RUN npm install

copy src src

CMD npm start