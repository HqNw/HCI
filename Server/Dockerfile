FROM node:20-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install -g nodemon
RUN npm install

COPY . .

EXPOSE 8080
CMD ["nodemon", "index.js"] 