FROM node:12.21-alpine

WORKDIR /app

COPY package.json yarn.lock ./

RUN yarn

COPY . ./

CMD [ "yarn", "watch" ]
