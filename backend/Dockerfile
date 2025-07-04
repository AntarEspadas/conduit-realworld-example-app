FROM node:24-alpine

RUN mkdir /app
WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3001

CMD [ "npm", "run", "start" ]