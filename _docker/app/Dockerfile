FROM node:20-alpine3.17 as build
WORKDIR /app
COPY package.json ./
RUN npm install
COPY . .
RUN NODE_ENV=development npm i