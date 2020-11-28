FROM node:14.8.0-buster-slim

WORKDIR /home/node/app
COPY . .

RUN apt-get update && \
    npm -g install 

COPY --chown=node:node . .

COPY . .

CMD ["node", "main.js"]