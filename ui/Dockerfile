FROM node:alpine

WORKDIR /webapp/ui

COPY package.json .

RUN npm i

COPY . .

WORKDIR /webapp/ui/src

RUN npm i

EXPOSE 3000

WORKDIR /webapp/ui

CMD ["npm", "start"]