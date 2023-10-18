FROM node:18-alpine

WORKDIR /api_express

COPY index.js .
COPY package*.json .

RUN npm install

CMD ["npm", "start"]