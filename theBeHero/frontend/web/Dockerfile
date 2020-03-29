FROM node:alpine

WORKDIR /usr/app

COPY package.jason ./
COPY
RUN yarn add

COPY . .

EXPOSE 3333

CMD ["yarn", "start"]
