FROM node:16-alpine

WORKDIR '/app'

COPY ./package.json .

RUN ls
RUN npm install

COPY . .

CMD [ "npm", "run", "build:dev" ]