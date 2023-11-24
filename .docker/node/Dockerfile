FROM node:18-alpine

RUN apk add --no-cache python3 make g++

RUN yarn global add @angular/cli

EXPOSE 4200

CMD ["yarn", "run", "start"]
