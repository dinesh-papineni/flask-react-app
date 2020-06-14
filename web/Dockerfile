FROM node:13.12.0-alpine

WORKDIR /app

COPY package*.json ./

RUN npm install -g

COPY . .

EXPOSE 8080

ENTRYPOINT [ "npm" ]
CMD [ "start" ]
