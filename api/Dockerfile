FROM node:alpine

WORKDIR /webapp/api

COPY package.json .

RUN npm i

EXPOSE 3001

COPY . .

RUN {"node", "index"}