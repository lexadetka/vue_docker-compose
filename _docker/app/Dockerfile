FROM node:12.18.1-alpine as build
WORKDIR /app
COPY package.json ./
RUN npm install
COPY . .
RUN NODE_ENV=development npm i