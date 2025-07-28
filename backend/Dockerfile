FROM node:18-alpine AS builder

WORKDIR /backend

COPY package*.json ./
RUN npm install

COPY . .

EXPOSE 3000

CMD ["node", "account.js"]