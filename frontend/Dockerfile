FROM node:latest as build
WORKDIR /app
COPY . /app
RUN npm install
WORKDIR /app/frontend/src
CMD ["npm" ,"run","start"]