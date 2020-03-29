FROM node:alpine

WORKDIR /usr/app

COPY package*.jason ./
RUN npm install

COPY . .

EXPOSE 3333

CMD ["npm", "start"]
