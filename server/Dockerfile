FROM node:18.4-slim

WORKDIR /app

COPY ./package.json ./
COPY ./yarn.lock ./

RUN yarn install 

COPY . .

EXPOSE 5000

CMD [ "yarn", "start" ]