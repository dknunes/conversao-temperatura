FROM node:current-alpine3.16

WORKDIR /app
COPY package*.json /app/
RUN npm install
COPY . .
CMD [ "node","server.js" ]
