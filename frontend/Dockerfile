FROM node:alpine

LABEL maintainer="Vic Shóstak <truewebartisans@gmail.com>"

WORKDIR /frontend
COPY package*.json ./
RUN npm install --only=production
COPY . .
RUN npm run build:prod
