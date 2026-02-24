FROM node:14

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

ExPOSE 80

CMD [ "node", "server.js" ]