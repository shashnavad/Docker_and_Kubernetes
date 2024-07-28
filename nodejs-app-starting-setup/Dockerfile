FROM node:19.5.0-alpine

WORKDIR /app

COPY . ./app

COPY package.json ./
COPY server.js ./

RUN npm install

EXPOSE 80

CMD ["node", "server.js"]