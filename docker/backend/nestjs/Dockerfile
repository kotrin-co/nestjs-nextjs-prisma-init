FROM node:20-slim

WORKDIR /server
COPY package*.json ./

RUN npm i -g @nestjs/cli

RUN yarn add -D prisma
RUN yarn add @prisma/client

RUN yarn install

COPY . .

CMD ["yarn", "start"]
