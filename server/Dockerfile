FROM node:10-alpine

RUN mkdir -p /app
WORKDIR /app

COPY package.json /app
COPY npm.lock /app
COPY . /app

RUN npm install

CMD ["npm", "start"]
