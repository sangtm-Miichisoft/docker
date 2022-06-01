FROM node:16-alpine3.14

LABEL maintainer="tungdk@miichisoft.net"

WORKDIR /var/www/docker-nestjs

COPY ./package*.json ./

EXPOSE 3000

CMD [ "sh", "-c", "yarn install && yarn run start" ]
