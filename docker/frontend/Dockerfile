FROM node:20-slim

WORKDIR /web
COPY package*.json ./

RUN yarn install

COPY . .

CMD ["yarn", "dev"]