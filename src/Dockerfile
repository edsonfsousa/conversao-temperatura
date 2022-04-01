# build stage
FROM node:carbon-alpine
WORKDIR /usr/src/app
COPY package*.json ./
RUN npm install

# production stage
COPY . ./
EXPOSE 80
CMD ["node","server.js"]