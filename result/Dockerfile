FROM node:10

RUN mkdir -p /app
WORKDIR /app

COPY package*.json /app/

RUN npm install

COPY ../worker /app

CMD [ "node", "index.js" ]