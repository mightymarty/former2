FROM node:14.8.0-buster-slim

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

ENTRYPOINT [ "node", "main.js" ]