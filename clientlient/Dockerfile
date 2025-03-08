FROM node:20.12.0

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 3001

COPY .env .env

CMD ["npm", "run", "start"]

