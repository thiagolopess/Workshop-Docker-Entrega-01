FROM node:12.21-alpine

WORKDIR /app

COPY package.json yarn.lock ./

RUN yarn

COPY . ./

RUN chmod +x ./start.sh

CMD ["/bin/sh", "/app/start.sh"]