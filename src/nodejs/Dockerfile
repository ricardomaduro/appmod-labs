FROM node:9.9.0-alpine

WORKDIR /app

COPY views ./views/
COPY public ./public/
COPY routes ./routes/
COPY bin ./bin/
COPY app.js .
COPY *.json ./

RUN npm install

EXPOSE 3000

CMD npm start
