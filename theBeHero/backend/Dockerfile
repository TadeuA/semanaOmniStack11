FROM node:alpine

WORKDIR /usr/app

COPY package*.jason ./
RUN npm install

COPY . .

EXPOSE 

CMD ["npm", "start"]